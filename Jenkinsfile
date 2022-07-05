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
        build(quietPeriod: 1, job: 'maven')
      }
    }

  }
}