pipeline {
  agent any
  stages {
    stage('git integration') {
      steps {
        echo 'git integrated'
      }
    }

    stage('build stage') {
      parallel {
        stage('build stage') {
          steps {
            bat 'echo hello'
          }
        }

        stage('code quality scan') {
          steps {
            echo 'code quality checking'
          }
        }

      }
    }

    stage('deploy') {
      steps {
        echo 'deployed'
      }
    }

  }
}