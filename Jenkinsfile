pipeline {
  agent any 
  stages {
    stage('working with conditions') {
      steps {
        script {
          for(i=1;i<=5;i++){
            println "my i value  is ${i}"
          }
          lis1 = ["devops","genai","aidevops"]
          for(j in lis1){
            println "my value is ${j} "
          }
          k=1
          while(k<=5){
            println "value of  k is: ${k}"
            k = k + 1
          }
        }
      }
    }
  }
}
