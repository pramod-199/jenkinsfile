pipeline {
  agent any
  stages {
    stage('script-test') {
      steps {
        git(url: 'https://github.com/pramod-199/spring-boot-war-example.git', branch: 'main', poll: true)
      }
    }

  }
}