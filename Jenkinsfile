pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
        sh 'echo "This is the first step towards Automation!"'
        }
    }
    stage ('Build Again') {
      steps {
        sh 'echo "This is the 2nd step towards Automation!"'
        sh 'ls -lh > store.txt'
        sh 'cat store.txt'
      }
    }
  }
}
