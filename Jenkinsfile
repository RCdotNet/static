pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
        sh 'echo "Hello Word"'
        sh '''
          sh "Multiline shell steps works too."
          ls -lah
        '''
      }
    }
  }
}
