pipeline {
  agent {
    node {
      label 'LIN6'
    }

  }
  stages {
    stage('build') {
      steps {
        archiveArtifacts(allowEmptyArchive: true, artifacts: 'tes')
      }
    }
  }
}