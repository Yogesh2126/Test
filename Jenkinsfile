pipeline{
    agent any
	  stages {
		  cleanWs()
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
