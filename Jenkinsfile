pipeline {
  agent any
  triggers {
    pollSCm('H/2 * * * *')
  }
  stages {
    stage('HelloWorld') {
      steps {
        echo 'Hello world!'
      }
    }
  }
}
    
