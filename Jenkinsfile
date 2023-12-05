pipeline {
  agent {
    node {
      label 'linexnode'
    }

  }
  stages {
    stage('stage1') {
      parallel {
        stage('stage1') {
          steps {
            sh 'echo "1 of 1"'
            echo '2 of 1'
          }
        }

        stage('stage2') {
          steps {
            sh 'echo "1 of 2"'
          }
        }

      }
    }

  }
}