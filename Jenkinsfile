pipeline{
    agent any
	
	  stages {
	stage ('Clean Workspace'){
		          steps {
			          cleanWs()
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
