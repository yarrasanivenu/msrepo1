pipeline {
  agent {
    node {
      label 'linexnode'
    }

  }
  stages {
    stage('stage1') {
      agent {
        node {
          label 'linexnode'
        }

      }
      steps {
        sh 'echo "1 of 1"'
        echo '2 of 1'
      }
    }

  }
}