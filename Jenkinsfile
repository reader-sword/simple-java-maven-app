pipeline {
    agent {
        docker {
            image 'sudo node:6-alpine' 
            args 'sudo -p 3000:3000' 
        }
    }
    stages {
        stage('Build') { 
            steps {
                sh ' sudo npm install' 
            }
        }
    }
}
