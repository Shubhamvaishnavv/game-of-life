pipeline {
		agent any
		stages {
			stage ("Build"){
				steps {
				    sh 'mvn clean install'
				}
			}
			stage ("Stage-2"){
				steps {
				    echo "Hello World two"
				}
			}
			stage ("Stage-3"){
			
				steps {				
				    echo "Hello World three"	
				}		
			}		
		}
}
