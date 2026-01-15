pipeline{
    agent any
	    triggers {
         pollSCM 'H/2 * * * *'
          }
   stages {
		 stage ('build'){
		          steps {
					  cleanWs()
			          sh 'ls-la'
			        }
		        }
         stage ('Test'){
		          steps {
			          sh 'python3 test.py'
				  }
		        }						
	    }
}
