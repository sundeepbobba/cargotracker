pipeline {
    agent none
    options {
        skipDefaultCheckout false
    }
stages {    
    stage('Setup') {
      agent {
        label "master"
      }    
      steps {
        sh "ls -ltr"
      }
    }
}
}
