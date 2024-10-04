def myfn(a,b){
    println "Welcome to Functions"
    println "my a value is ${a} & my b value is ${b}"
}

pipeline{
    agent any
    stages {
        stage("Welcome to Jenkins") {
            steps {
                script {
                    // Calling a function
                    myfn(200,400)
                }
            }
        }
        
    }
}
