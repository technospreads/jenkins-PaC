pipeline {
agent any
stages{
   stage("Working with conditions"){
     steps{
      script{
           a=input message: 'Please enter A value', parameters: [string(defaultValue: '10', description: 'Please enter A value', name: 'a')]
           b=input message: 'Please enter B value', parameters: [string(defaultValue: '20', description: 'Please enter A value', name: 'b')]
           if (a>b){
           println "here is your A is big"
           }
           else{
            println "here is your B is big"           
           }
          }    
       }  
     }
   }
}
