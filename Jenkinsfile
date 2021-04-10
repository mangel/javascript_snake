pipeline {
  agent {
    node {
      label 'label'
    }

  }
  stages {
    stage('Publish') {
      steps {
        archiveArtifacts '*'
      }
    }

  }
}