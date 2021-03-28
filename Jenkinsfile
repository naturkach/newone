pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
        echo 'Running build automation' > testf        
        archiveArtifacts artifacts: 'dist/test.zip'        
      }
    }    
  }
}
