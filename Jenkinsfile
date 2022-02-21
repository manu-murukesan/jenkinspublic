pipeline{
	agent any
	def toolbelt = tool 'toolbelt'
	stages {
		stage("build"){
			steps{
				//sh '' //steps
				echo 'building the application'
				echo 'wohooo... success'
				
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
