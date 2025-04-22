pipeline {
  agent any
  stages {
    stage('Testing') {
      steps {
        sh '''ls
pwd
echo "This is first stage of Jenkins blue ocean project"'''
      }
    }

    stage('Build') {
      steps {
        sh 'echo "This is build stage"'
      }
    }

  }
}