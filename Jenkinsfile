pipeline {
	agent any 
	
	stages {
	    stage('Checkout') {
      	        steps {
			checkout scm			       
		      }}
		stage('Build') {
	           steps {
			  sh '/home/harshada/Documents/DevOps_software/apache-maven-3.9.6/bin/mvn install'
	                 }}
		stage('Deployment'){
		   steps {
		sh 'cp target/MATRIMONY.war /home/harshada/Documents/DevOps_software/apache-tomcat-9.0.88'
			}}	
}} 
