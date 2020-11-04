node('master')

{

stage('Continuous Download') 
   
	 {
	
    git 'https://github.com/hadoopkumar07/maven.git'
    
	}

stage('Continuous build') 
   
	 {
	
   sh label: '', script: 'mvn package'
	}
}
