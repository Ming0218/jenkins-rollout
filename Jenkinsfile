pipeline {
  agent any
  stages {
    stage('') {
      steps {
        echo 'hello'
        git(url: 'https://github.com/Ming0218/jenkins-rollout', credentialsId: 'dockerhub', poll: true)
      }
    }

  }
}