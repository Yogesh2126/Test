pipeline{
    agent any
	cleanWs()
	  stages {
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
