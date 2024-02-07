pipeline {
    agent any
    stages {
        stage ('docker') {
            steps {
              docker.build("dockerimage", "-f D:\\Docker\\image\\ .")
            }
        }
        stage ('notify') {
            steps {
                echo "build sucess"

            }
          
        }
        
    }
}