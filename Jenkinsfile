pipeline{
  agent any
  stages {
    stage ('Build'){
      steps{
        echo 'Runnning build automation'
        sh .'./gralew build --no-daemon'
        archivedArtifacts artifacts: 'dist/trainSchedule.zip'  
      }
    }
  }
}
