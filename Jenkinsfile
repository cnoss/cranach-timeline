pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'cd frontend && npm install && npm run build'
      }
    }

  }
}