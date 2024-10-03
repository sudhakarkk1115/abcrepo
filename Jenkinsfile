pipeline{
    agent any
    parameters{
        choice choices: ['dev', 'test', 'pt', 'prod'], description: 'select environment', name: 'ENV'
    }
    environment {
        JAVA_HOME = "/usr/bin/java8"
    }
    stages {
        stage("Welcome to Jenkins") {
            steps {
                script {
                    // Printing default variables
                    println "BUILD_NUMBER is ${BUILD_NUMBER}"
                    println "WORKSPACE is ${WORKSPACE}"

                    //Printing the parameter values
                    println "Selected env is ${params.ENV}"    

                    // printing environment variables
                    println "My java home path is ${env.JAVA_HOME}"   
                                     
                }
            }
        }
        
    }
}
