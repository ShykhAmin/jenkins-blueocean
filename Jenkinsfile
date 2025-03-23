pipeline {
  agent any
  stages {
    stage('Test') {
      steps {
        sh 'echo "Testing the Project"'
      }
    }

    stage('Build') {
      steps {
        echo 'Building the Project'
        sleep 10
      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploying the Project'
        sh 'echo "deploying the project"'
      }
    }

  }
}