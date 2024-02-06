pipeline {
    agent any
    stages {
        stage ('docker') {
            steps {
              docker.build("dockerimage:Docker")
            }
        }
        
    }
}