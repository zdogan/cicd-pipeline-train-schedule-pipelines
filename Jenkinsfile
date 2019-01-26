pipeline {
  agent any
  stages {
    stage ('Built') {
      steps {
        echo 'Running build automation'
        sh './gradlew build --no-daemon'
        archiveArtifacts artifacts: 'dist/trainschedule.zip'
   }
  }
 }
}
   
