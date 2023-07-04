def myfunction(int a , int b){
result = a+b 
println "Here is my function result ${result}"
}

pipeline 
{
agent any
stages{
   stage("Working with Loops"){
     steps{
      script{
        myfunction(10,20)
        myfunction(10,200)
        
          }    
       }  
     }
   }
}
