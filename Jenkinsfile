pipeline {
  agent any
  stages {
    stage('Checkout Code') {
      steps {
        git(url: 'https://github.com/zezo-rgb/Curriculum-App', branch: 'main')
      }
    }

    stage('Log') {
      steps {
        sh '''ls -la 
'''
      }
    }

  }
}