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
    stage('Clean-up Cache') {
      steps {
		sh "mvn clean"
    }
}
stage('Install Dependencies') {
      steps {
                sh "mvn dependency:resolve"
    }
}
stage('Perform Unit Test') {
      steps {
                sh "mvn test"
    }
}
stage('Package Application') {
      steps {
                sh "mvn package"
    }
}


}
}
