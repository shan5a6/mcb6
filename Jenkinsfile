pipeline {
  agent any 
  parameters {
    choice choices: ['dev', 'prod'], description: 'select environment', name: 'ENV'
  }
  environment {
      JAVA_HOME = "/opt/bin/java11"
    }
  stages {
    stage('welcome') {
      steps {
        script {
          // user  defined 
          var1 = 20
          println "value of var1 is ${var1}"
          // default variables
          println "my workspace is ${WORKSPACE}"
          // using parameters section 
          println "Selected environment is ${params.ENV}"
          // using environment variables 
          println "My java version is ${env.JAVA_HOME}"
        }
      }
    }
  }
}
