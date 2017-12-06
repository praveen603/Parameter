pipeline {
    agent any
    parameters {
        string(name: 'ENVIRONMENT   ', defaultValue: 'Integration', description: 'Select required environment.')
        boolean(name: 'REBUILD   ', defaultValue: '', description: 'Should we rebuild the database')

    }
    stages {
        stage('Example') {
            steps {
                echo "Hello ${params.PERSON}"
            }
        }
    }
}
