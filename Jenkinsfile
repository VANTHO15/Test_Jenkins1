pipeline {
  agent any
  stages {
    stage('a') {
      steps {
        echo 'aaaa'
      }
    }

    stage('Buzz Build') {
      steps {
        archiveArtifacts(artifacts: 'target/*.jar', fingerprint: true)
      }
    }

  }
}