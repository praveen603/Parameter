pipeline {
    agent any
    parameters {
        string(name: 'ENVIRONMENT   ', defaultValue: 'Integration', description: 'Select required environment.')
    
       booleanParam(name: 'DEBUG', defaultValue: false, description: 'check the box if you want to debug') 
       booleanParam(name: 'DEPLOY', defaultValue: false, description: 'check the box if you want to deploy') 
       choice(choices: 'Branch1\Banch2\Branch3', description: 'Choose the branch which you want to build', name: 'BRANCH')
     

    }
    
    stages {
        stage('Example') {
            steps {
                echo "Hello ${params.ENVIRONMENT}"
            }
        }
        
        
        
        
        
    }    
   
}

