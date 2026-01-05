pipeline{
    agent any
	  stages {
	   
	     //stage ('code push by developer'){
	             steps {
                      git branch: 'main', credentialsId: '001', url: 'https://github.com/Yogesh2126/Test.git'  
			        }
	            }
		 stage ('build'){
		          steps {
			          sh 'ls'
					  sh 'pwd'
			        }
		        }
         stage ('Test'){
		          steps {
			          sh './abc.sh'
			        }
		        }						
	    }
}
