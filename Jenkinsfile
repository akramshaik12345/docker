pipeline {
    agent any
    stages {
        stage ('docker') {
            steps {
              docker.build("dockerimage:D:\Docker")
            }
        }
        stage ('notify') {
            steps {
                echo "build sucess"

            }
          
        }
        
    }
}