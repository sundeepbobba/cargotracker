pipeline {
    agent any
    options {
        skipDefaultCheckout false
    }
stages {    
    stage('Setup') {
      steps {
	 withMaven(maven : 'MVN') {
		sh "mvn install"
      }
    }
}
}
}
