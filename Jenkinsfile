pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'echo "Hello World"'
        sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
      }
    }
    stage('Test') {
      steps {
        input 'GMUD em Produ��o (Click "Approved" to continue)'
      }
    }
  }
}