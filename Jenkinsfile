pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        timeout(time: 20, activity: true)
      }
    }
  }
  environment {
    var1 = '10'
    var2 = '20'
  }
}