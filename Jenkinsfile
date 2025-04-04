pipeline {
    agent any
    
    
    stages {
        stage('Checkout Code') {
            steps {
                echo "working"
            }
        }
        stage('Verify Files') {
            steps {
                sh '''
                    echo "Checking project files..."
                    ls -la
                    pwd
                    echo "\n=== main.py ==="
                    cat main.py
                    echo "\n=== Dockerfile ==="
                    cat Dockerfile
                    echo "\n=== requirements.txt ==="
                    cat requirements.txt
                '''
            }
        }
        
    
    }
}
