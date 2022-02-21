pipeline{
	agent any
	stages {
		stage("build"){
			steps{
				//sh '' //steps
				echo 'building the application'
				echo 'wohooo... success'
				sh "C:\Program Files\Salesforce CLI\bin\sfdx.cmd"
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
