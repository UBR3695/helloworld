pipeline {
  agent any
  stages {
    stage('SCM config') {
      steps {
        git(url: 'https://github.com/UBR3695/helloworld', branch: 'master')
      }
    }

    stage('Build') {
      steps {
        sh 'git --version'
      }
    }

  }
}