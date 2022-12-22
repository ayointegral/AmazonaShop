pipeline {
  agent any
  stages {
    stage('npm install') {
      steps {
        sh 'npm install'
      }
    }

    stage('run dev') {
      steps {
        sh 'npm run dev'
      }
    }

  }
}