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
        input 'GMUD em PRD? (Clique em "Proceed" para aprovar)'
        sleep 10
      }
    }
  }
}