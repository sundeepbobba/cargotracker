pipeline {
    agent any
    options {
        skipDefaultCheckout false
    }
stages {    
    stage('Setup') {
      steps {
        sh "mvn install"
      }
    }
}
}
