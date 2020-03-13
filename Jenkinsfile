pipeline {
  agent {
    node {
      label 'dl1'
    }

  }
  stages {
    stage('start') {
      steps {
        echo 'calling Job SN1'
      }
    }

    stage('build') {
      steps {
        build 'sn1'
      }
    }

  }
}