pipeline {
    agent any
    parameters {
        string(name: 'ENVIRONMENT   ', defaultValue: 'Integration', description: 'Select required environment.')
    }
    
     parameters {
        Choice(name: 'ENVIRONMENT   ', defaultValue: 'Integration', description: 'Select required environment.')
    }
     parameters {
        boolean(name: 'ENVIRONMENT   ', defaultValue: 'Integration', description: 'Select required environment.')
    }
    
    
    
    
    
    
    
    
    
    
    
    stages {
        stage('Example') {
            steps {
                echo "Hello ${params.PERSON}"
            }
        }
    }
}
