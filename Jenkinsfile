[200~pipeline {
	agent {
		label{
				label "built-in"
				customWorkspace "/data/pipeline"
		
		}
	}
	
	stages {
			stage ('one') {
					steps {
							 sh "echo 'Hello all' > dev.html"
					}
			}
			
			stage ('two') {
					steps {
					dir ('/data/pipeline/qa'){
							 sh "echo 'Hello all' > qa.html"
							 
							 }
					}
			}
			
	
	}

}
