pipeline {
  agent any
  stages {
    stage('Polling') {
      steps {
        git(url: 'https://github.com/rohanjoseph/angularBlueocean.git', branch: 'development', poll: true, credentialsId: 'rohanjoseph89')
      }
    }
  }
}