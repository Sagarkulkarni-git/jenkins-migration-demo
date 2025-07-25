pipeline {
  agent any

  environment {
    APP_ENV = 'dev'
  }

  stages {
    stage('Checkout') {
      steps {
        git 'https://github.com/Sagarkulkarni-git/jenkins-migration-demo.git'
      }
    }

    stage('Build') {
      steps {
        sh 'echo "Building app..."'
      }
    }

    stage('Deploy') {
      steps {
        sh 'echo "Deploying app..."'
      }
    }
  }
}
