pipeline {
  agent any
  stages {
    stage('Test') {
      steps {
        sh '''echo "Testing the Project"
mvn --version'''
        tool(name: 'Maven', type: 'Maven')
      }
    }

    stage('Build') {
      steps {
        echo 'Building the Project'
        sleep 10
      }
    }

    stage('Deploy on test') {
      steps {
        echo 'Deploying the Project'
        sh 'echo "deploying the project"'
      }
    }

    stage('Deploy on prod') {
      steps {
        sh 'echo "deploying on prod"'
      }
    }

  }
}