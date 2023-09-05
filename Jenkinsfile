pipeline {
  agent any
  stages {
    stage('Plan') {
      steps {
        echo 'I have a plan to work on CICD'
      }
    }

    stage('Code') {
      steps {
        echo 'I have code for CICD project'
      }
    }

    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'I have build the code for CICD project'
          }
        }

        stage('Test') {
          steps {
            echo 'I have tested the code for CICD project'
          }
        }

        stage('Release') {
          steps {
            echo 'I have release the work off CICD project'
          }
        }

        stage('Deploy') {
          steps {
            echo 'I have deployed the work on CICD project'
          }
        }

        stage('Operate') {
          steps {
            echo 'I have operate the work on CICD project'
          }
        }

      }
    }

  }
}