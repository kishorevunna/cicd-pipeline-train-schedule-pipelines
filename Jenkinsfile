pipeline {
  agent any
  stages {
    stage {"Build") {
      steps {
      echo 'running building automation'
      sh './gradlew build --no- daemon'
      archiveArtifacts artifacts: ' dist/trainSchedule.zip'
     }
    }
   }
  }
