pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Building..'
        timestamps()
      }
    }
    stage('Test') {
      steps {
        echo 'Testing A..'
      }
    }
    stage('Deploy') {
      steps {
        echo 'Deploying....'
      }
    }
  }
}