def myfunction(int a , int b){
   
result = a + b  
}

pipeline 
{
agent any
stages{
   stage("Working with conditions"){
     steps{
      script{

         myfunction(100,200)
         println "here is your function value ${result}"
          }    
       }  
     }
   }
}
