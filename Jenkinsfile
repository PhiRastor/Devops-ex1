pipeline {
  agent any
  triggers {
    pollSCM('H/2 * * * *')
  }
  
  stages {
    stage('HelloWorld') {
      steps {
        echo 'Hello world!!!!!'
      }
    }
    stage("Hello world again !"){
        steps{
         echo 'Hello world again !'   
    }
    }
  }
}
    
