pipeline{
	agent any
	tools {
		// Install the Maven version configured as "M3" and add it to the path.
		sfdx "sfdx"
	    }
	stages {
		stage("build"){
			steps{
				//sh '' //steps
				echo 'building the application'
				echo 'wohooo... success'
				sh "sfdx"
				//rc = command "${toolbelt}/sfdx"
			}
		}
		
		stage("deploy"){
			steps{
				echo 'deploying the application'
			}
		}
	}
}

//groovy script
