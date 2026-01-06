pipeline{
    agent any
	
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
					  sh 'python3 test.py'
					  
			        }
		        }						
	    }
}
