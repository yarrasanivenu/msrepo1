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

        stage('stage2') {
          agent {
            node {
              label 'linexnode'
            }

          }
          steps {
            sh 'echo "1 of 2"'
            sh '2 of 2'
          }
        }

      }
    }

  }
}