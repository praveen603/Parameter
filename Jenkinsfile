pipeline {
    agent any
    parameters {
        string(name: 'ENVIRONMENT   ', defaultValue: 'Integration', description: 'Select required environment.')
    
 booleanParam(name: 'DEBUG_BUILD', defaultValue: true, description: '') 
    }
    
    stages {
        stage('Example') {
            steps {
                echo "Hello ${params.ENVIRONMENT}"
            }
        }
        
        
        
        
        
    }    
   
}

