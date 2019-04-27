pipeline {
  agent {
    node {
      label 'myslave'
    }

  }
  stages {
    stage('Build') {
      steps {
        echo 'This is the Build Stage'
        sh 'sh \'echo building..\''
      }
    }
  }
}
