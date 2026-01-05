pipeline{
    agent any
	
	  stages {
		 stage ('build'){
		          steps {
					  cleanWs()
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
