pipeline {
  agent any
  stages {
    stage("verify tools"){
      steps {
        sh '''
          ls -l
          curl --version
        '''
      }
    }
  }
}
