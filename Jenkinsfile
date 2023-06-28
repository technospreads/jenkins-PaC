pipeline {
agent any
stages {
   stage("This is my first stage"){
    steps{
      script{
          var1 = 10
          println "my variable value is ${var1}"
          println " Hello here is your predefined variable ${currentBuild.result}"
          println " Hello here is your predefined variable ${currentBuild.id}"
          println " Hello here is your predefined variable ${currentBuild.fullProjectName}"

         } 
      }
    }
   }
}
