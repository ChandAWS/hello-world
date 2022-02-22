pipeline {
    agent any

    stages {
        stage('Git Checkout') {
            steps {
                git 'https://github.com/ChandAWS/hello-world.git'
            }
        }
        
         stage('Build') {
            steps {
                echo "Some code compilation here"
            }
        }
        
          stage('Test') {
            steps {
                echo "Some test execution here"
            }
        }
        
          stage('Deploy') {
            steps {
                echo "Deployed successfully"
            }
        }
        
          stage('Validate') {
            steps {
                echo "Validated successfully"
            }
        }
    }
}
