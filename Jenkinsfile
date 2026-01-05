pipeline{
    agent any
	
	  stages {
		  stage ('Workspace clean'){
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
