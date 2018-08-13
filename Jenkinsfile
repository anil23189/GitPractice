pipeline {
  agent {
    dockerfile {
      filename 'reddy'
    }

  }
  stages {
    stage('build') {
      steps {
        build 'reddy'
      }
    }
  }
  environment {
    re = 'rt'
  }
}