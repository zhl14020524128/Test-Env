pipeline {
  agent any
  stages {
    stage('GetCode') {
      steps {
        bat 'echo "git pull"'
      }
    }

    stage('Build') {
      steps {
        echo 'Build Start'
      }
    }

    stage('Test') {
      steps {
        bat 'echo "Test Project"'
      }
    }

  }
}
