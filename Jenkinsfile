pipeline {
  agent {
    dockerfile {
      filename 'Dockerfile-BN128'
    }

  }
  stages {
    stage('Initilization') {
      steps {
        echo 'Download Dependencies'
      }
    }

    stage('Build') {
      steps {
        echo 'build stuff'
      }
    }

    stage('Testing') {
      steps {
        echo 'Testing stuff'
      }
    }

  }
  environment {
    TEST = 'testvalue'
  }
}