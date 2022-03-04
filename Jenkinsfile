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
	 withMaven(maven : 'MVN') {
		sh "mvn install"
      }
    }
}
}
}
