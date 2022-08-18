pipeline {
  agent any
  tools {
  maven 'maven'
  }
    stages {

	stage ('Build')  {
	    steps {
            sh "mvn package"
        }    
   }

  }
  }
