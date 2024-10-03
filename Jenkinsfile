pipeline{
    agent any
    parameters{
        choice choices: ['dev', 'test', 'pt', 'prod'], description: 'select environment', name: 'ENV'
    }
    stages {
        stage("Welcome to Jenkins") {
            steps {
                script {
                    // Printing default variables
                    println "BUILD_NUMBER is ${BUILD_NUMBER}"
                    Println "WORKSPACE is ${WORKSPACE}"

                    //Printing the parameter values
                    println "Selected env is ${params.ENV}"       
                                     
                }
            }
        }
        
    }
}
