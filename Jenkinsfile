pipeline{
    agent any
    stages {
        stage("Welcome to Jenkins") {
            steps {
                script {
                    // reading lines from file
                    File myfile = new File("/tmp/test.txt")
                    lines = myfile.readLines()
                    // Printing all the lines
                    println lines
                    // printing each line
                    for(line in lines) {
                        println line
                    }                    
                }
            }
        }
        
    }
}
