def welcom_note(){
  println "Hey thanks for calling, welcome to dvs mcd"
}

def addition(a,b){
  sum = a + b 
  println "addition of ${a} & ${b} is: ${sum}"
}
pipeline {
  agent any 
  stages {
    stage('welcome') {
      steps {
        script {
          welcom_note() // calling the function
          addition(300,400)
        }
      }
    }
  }
}
