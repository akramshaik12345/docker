pipeline {
    agent any
    stages {
        stage ('docker') {
            steps {
              docker.build("dockerimage:D:\Docker\image\Dockerfile")
            }
        }
        stage ('notify') {
            steps {
                echo "build sucess"

            }
          
        }
        
    }
}