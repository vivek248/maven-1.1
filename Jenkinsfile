pipeline {
  agent any
  stages {
    stage('git fetch') {
      steps {
        git(url: 'git@github.com:vivek248/maven-1.1.git', branch: 'main/clover')
      }
    }

    stage('maven clean install ') {
      steps {
        sh 'mvn clean install'
      }
    }

  }
}