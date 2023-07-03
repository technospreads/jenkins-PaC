def myfunction(int a , int b,string opr){
   println "${opr}"
result = a opr b  
}

pipeline 
{
agent any
stages{
   stage("Working with conditions"){
     steps{
      script{
        
        myfunction(10,20,'+')
         println "here is your function value ${result}"
         myfunction(100,200,'-')
         println "here is your function value ${result}"
          }    
       }  
     }
   }
}
