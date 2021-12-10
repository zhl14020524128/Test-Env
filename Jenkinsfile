pipeline {
  agent any
  stages {
    stage('GetCode') {
      steps {
        sh 'echo "git pull"'
      }
    }

    stage('Build') {
      steps {
        echo 'Build Start'
      }
    }

    stage('Test') {
      steps {
        sh 'echo "Test Project"'
      }
    }

  }
}