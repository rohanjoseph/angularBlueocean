pipeline {
  agent any
  stages {
    stage('Polling') {
      steps {
        git(url: 'https://github.com/rohanjoseph/angularBlueocean.git', branch: 'development', poll: true, credentialsId: '5b4c5c52-68b7-4b12-bc83-c6928c358e01')
      }
    }
  }
}