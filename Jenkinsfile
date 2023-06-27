pipeline {
agent any
stages {
   stage("This is my first stage"){
    steps{
      script{
          var1 = 10
          input message: 'Please enter a value ', parameters: [string(defaultValue: '10', name: 'a')]
          println "my variable value is ${var1}"

         } 
      }
    }
   }
}
