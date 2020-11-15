pipeline {
  agent any
  stages {
   stage ('build') {
    steps{
      echo 'Running build automation'
      sh '/gradlew --no-daemon'
      archiveArtifacts artifacts: 'dist/trainSchedule.zip'
      
      
        }  
    }
  }
}
