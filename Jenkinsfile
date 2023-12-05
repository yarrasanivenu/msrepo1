pipeline {
  agent {
    node {
      label 'linexnode'
    }

  }
  stages {
    stage('stage1') {
      agent any
      steps {
        sh 'echo "1 of 1"'
        echo '2 of 1'
      }
    }

  }
}