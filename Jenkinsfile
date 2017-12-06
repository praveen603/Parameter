pipeline {
    agent any
    parameters {
        string(name: 'ENVIRONMENT   ', defaultValue: 'Integration', description: 'Select required environment.')
    
       booleanParam(name: 'DEBUG_BUILD', defaultValue: true, description: 'check the box if you want to debug') 
       booleanParam(name: 'DEPLOY', defaultValue: true, description: 'check the box if you want to debug') 

    }
    
    stages {
        stage('Example') {
            steps {
                echo "Hello ${params.ENVIRONMENT}"
            }
        }
        
        
        
        
        
    }    
   
}

