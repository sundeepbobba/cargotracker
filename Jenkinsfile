pipeline {
    agent any
tools {
        maven "MVN"
    }
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
