pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Running build automation' > test.txt
                archiveArtifacts artifacts: 'test.txt'
            }
        }
        stage('Build Docker Image') {           
            steps {
                script {
                    app = docker.build("naturkach/mybuild)
                    app.inside {
                        sh 'echo Hello, World!'
                    }
                }
            }
        }
   }
}

