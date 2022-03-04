pipeline {
    agent any
    options {
        skipDefaultCheckout false
    }
stages {    
    stage('Setup') {
      steps {
        sh "sudo mvn install"
      }
    }
}
}
