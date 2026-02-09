pipeline {
  agent any 
  stages {
    stage('file-handling') {
      steps {
        script {
           File file = new File("/tmp/test.txt")
           def lines = file.readLines()
           println "Lines\n ${lines}"
           for (line in lines) {
             println "myline is ${line}"
           }
        }
      }
    }
  }
}
