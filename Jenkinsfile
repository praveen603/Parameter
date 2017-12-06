pipeline {
    agent any
    parameters {
        string(name: 'ENVIRONMENT   ', defaultValue: 'Integration', description: 'Select required environment.')
        choice(name: 'Build   ', Choices: 'Integration,hbdkbkd', description: 'Select required environment.')

        
    }
    stages {
        stage('Example') {
            steps {
                echo "Hello ${params.ENVIRONMENT}"
            }
        }
        
        
        
        
        
    }    
   
}

