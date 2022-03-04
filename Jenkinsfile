pipeline {
    agent any
tools {
        maven "MVN"
        jdk "jdk8"
    }
    options {
        skipDefaultCheckout false
    }
stages {    
    stage('Setup') {
      steps {
                sh "java -version"
		sh "mvn install"
    }
}
}
}
