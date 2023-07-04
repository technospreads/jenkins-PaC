def myfunction(int a , int b){
result = a+b 
return result
}

pipeline 
{
agent any
stages{
   stage("Working with Loops"){
     steps{
      script{
        println "here is my first time calling function" + myfunction(10,20)
        println "here is my first time calling function " + myfunction(10,200)
        
          }    
       }  
     }
   }
}
