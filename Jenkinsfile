pipeline {
  agent any
  stages {
    stage('Master') {
      parallel {
        stage('Master') {
          steps {
            echo 'Master'
          }
        }
        stage('Gtest') {
          steps {
            echo 'Gtest'
          }
        }
      }
    }
  }
}