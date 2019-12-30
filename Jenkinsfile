pipeline {
  agent any
  stages {
    stage('') {
      agent {
        docker {
          image 'test'
        }

      }
      steps {
        sh 'ls'
        timeout(time: 300)
      }
    }
  }
}