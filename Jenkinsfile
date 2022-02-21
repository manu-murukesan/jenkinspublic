pipeline{
	agent any
	stages {
		stage("build"){
			steps{
				//sh '' //steps
				echo 'building the application'
				echo 'wohooo... success'
				def toolbelt = tool 'toolbelt'
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
