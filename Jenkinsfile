pipeline {
<<<<<<< HEAD
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Running build automation'
//                archiveArtifacts artifacts: 'test.txt'
            }
        }
//       stage('Build Docker Image') {           
//            steps {
//                script {
//                       app = docker.build("naturkach/mybuild)                   
//                       }
//                  }
//        }
    }
=======
  agent any
  stages {
    stage ('Build') {
      steps {
        echo 'Running build automation' > testf        
        archiveArtifacts artifacts: 'dist/test.zip'        
      }
    }    
  }
>>>>>>> 334cc5c6fce323024a67af6d5a76647097b90b26
}
