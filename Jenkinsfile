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
          agent any
          steps {
            sh 'echo "1 of 1"'
            echo '2 of 1'
          }
        }

        stage('stage2') {
          agent any
          steps {
            sh 'echo "1 of 2"'
            sh '2 of 2'
          }
        }

      }
    }

  }
}