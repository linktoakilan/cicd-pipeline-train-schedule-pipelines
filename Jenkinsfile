pipeline {
  agent any
  stages {
    stage ('Build') {
     steps {
      echo ('Running Build Automation')
      sh './gradlew build --no-daemon'
      archiveArtifacts artifacts: 'dist/trainShedule.zip'
     }    
    }
  }
}
