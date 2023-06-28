pipeline {
agent any
environment {
  SUBJECT = "Jenkins-PaC"
  BatchNo = "1"
}
parameters {
  choice choices: ['Dev', 'QA', 'PreProd', 'Prod'], description: 'Please select environment. ', name: 'Please select environment '
  string defaultValue: 'Devops', description: 'Here is your subject value.', name: 'Subject'
}

stages {
   stage("This is my first stage"){
    steps{
      script{
          var1 = 10
          println "my variable value is ${var1}"
          println " Hello here is your predefined variable ${currentBuild.result}"
          println " Hello here is your predefined variable ${currentBuild.id}"
          println " Hello here is your predefined variable ${currentBuild.fullProjectName}"

         println " Here is my environment variable of Subject ${env.SUBJECT}"
         println " Here is my environment variable of BatchNo ${env.BatchNo}"
          println " Here is my environment variable of Branch Name ${env.JOB_NAME}"

        println " Here is your Parameterised variable ${params.Subject}"
        println " Here is your Parameterised variable ${params.env}"

         } 
      }
    }
   }
}
