pipeline {
		agent any
		stages {
			stage ("Build"){
				steps {
				    sh 'mvn clean install'
				}
			}
			stage ("deploy"){
				steps {
				    sh'cp /var/lib/jenkins/workspace/Multibranch_book/target/onlinebookstore-0.0.1-SNAPSHOT.war /root/tomcat/webapps/book.sh'
				}
			}
			stage ("Stage-3"){
			
				steps {				
				    echo "Hello World three"	
				}		
			}		
		}
}
