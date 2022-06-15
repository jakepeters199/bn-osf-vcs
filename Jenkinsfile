pipeline {
  agent {
    docker {
      image 'openjdk:18.0.1.1-jdk'
      args '-p 3000:3000'
    }

  }
  stages {
    stage('init') {
      steps {
        sh 'java -version'
      }
    }

  }
}