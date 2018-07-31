pipeline {
  agent any
  stages {
    stage ('Buikd') {
      steps {
        echo 'Running build automation'
        sh './gradlew build --no-daemon'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip
      }
    }
  }
}
