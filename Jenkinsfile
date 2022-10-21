pipeline {
  agent any
  stages {
    stage('build') {
      parallel {
        stage('build') {
          steps {
            echo 'echo hi'
          }
        }

        stage('deploy') {
          steps {
            echo 'never'
          }
        }

      }
    }

    stage('terr') {
      steps {
        echo 'nn'
      }
    }

  }
}