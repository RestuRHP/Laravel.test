pipeline{

	agent any	
	
	stages{
	
		stage("build"){
		
			steps{
        			bat "ipconfig"
				echo 'building the application...'
				echo 'the application is built'
			}
		}
		stage("test"){
		
			steps{
				echo 'testing the application...'
			}
		}
		stage("deploy"){
		
			steps{
				echo 'deploying the application...'
			}
		}
	}	
}
