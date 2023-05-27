pipeline {
	agent any
	
	stages {
	    stage('Checkout') {
	        steps {
			checkout scm			       
		      }}
		stage('Build') {
	           steps {
			  sh '/usr/share/maven/mvn install'
	                 }}
		stage('Deployment'){
		    steps {
			
			sh 'cp target/flipkart.war /tmp'
	}
}}}
