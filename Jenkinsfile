pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''echo "Hello World"

'''
        sh '''echo "Multi line shell steps works too"
ls -lah'''
      }
    }
    stage('End') {
      steps {
        echo 'Done with the pipeline'
      }
    }
  }
  environment {
    Build = ''
  }
}