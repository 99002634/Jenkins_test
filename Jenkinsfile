
pipeline {
    agent any
    stages {
        stage('One') 
        {
                steps 
                {
                        echo 'Hi, Harsha C A'    
                }
        }
	      stage('Two')
        {
		            steps 
                {
			                  input('Do you want to proceed?')
                }
	      }
        stage('Three') 
        {
                       when 
                       {
                        not 
                        {
                                branch "main"  
                        }
                       }
                steps {
			                        echo "Hello All "
                       }
        }
      }
    }
