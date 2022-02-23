pipeline {
    agent any

    stages {
        stage('Git Checkout') {
            steps {
                checkout([$class: 'GitSCM', branches: [[name: '*/master']], extensions: [], userRemoteConfigs: [[credentialsId: 'dbea382b-2da8-4e8d-9695-e8ba5b711d89', url: 'https://github.com/ChandAWS/hello-world.git']]])
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
