pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''echo building
'''
        sh 'sh \'mvn\''
      }
    }

    stage('test') {
      steps {
        sh 'echo testing'
      }
    }

    stage('Deploy') {
      steps {
        sh 'echo deploying'
      }
    }

  }
}