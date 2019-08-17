pipeline { 
    agent any
    stages {
	stage('...clean..') {
	    steps {
	       bat "mvn clean"
	   }
        }
        stages {
	stage('...tests..') {
	    steps {
	       bat "mvn test"
	   }
        }
	stages {
	    stage('...packages...') {
	    steps {
	       bat "mvn package"
	   }
        }
  }
}
