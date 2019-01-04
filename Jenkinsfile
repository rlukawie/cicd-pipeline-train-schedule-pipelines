pipeline {
  agent any
  stages {
    stage ('Build') { 
      steps {
        echo 'Runnibng build autonation'
        sh './gradlew build --no-deamon'
        archiveArtifacts artifacts: 'dist/trainSchgedule.zip'
      }
    }
  }
}
