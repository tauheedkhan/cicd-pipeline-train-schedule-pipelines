pipeline {
  agent any
  stages {
    stage ('build'){
      steps {
      echo 'Running build automation'
      sh './gradlew build --no-daemon'
      archieveArtifacts artifacts: 'dist/train.zip'
      
      }
    
    }
  
  }
}
