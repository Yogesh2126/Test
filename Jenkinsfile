pipeline{
    agent any
	    triggers {
           pollSCM ('H/2 * * * *')
         }
   stages {
		 stage ('build'){
		          steps {
			          sh 'ls-la'
					  sh 'pwd'
			        }
		        }
         stage ('Test'){
		          steps {
			          sh 'python3 test.py'
				  }
		        }						
	    }
}
