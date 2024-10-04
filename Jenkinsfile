def myfn(a=2000,b=3000){
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
                    myfn()
                    myfn(200,400)
                    myfn(100)
                }
            }
        }
        
    }
}
