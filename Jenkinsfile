pipeline {
  agent any
  stages {
    stage("verify tools"){
      steps {
        sh '''
          ip a
          curl --version
        '''
      }
    }
  }
}
