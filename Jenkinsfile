pipeline {
    agent any
    stages {
        stage("build"){
	    steps {
	       sh "echo Integrating Jenkins pipeline with github webohook using jenkinsfile"
	       sh "ls"
	       sh "echo configuration on pipeline works"
	       sh "python --version"
	       sh "python pipeline.py"
	       }

	    }  
	
	stage("deployment") {
	    steps {
	       sh "echo deployment stage has been completed"
	       sh "echo good bye"
	       sh "kubectl --version"
	       sh "git --version"
	       }

	    }
	
	}


}	
