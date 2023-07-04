def myfunction(int a=1 , int b=5){
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
        ravi= println "here is my first time calling function1===" + myfunction(10,20)
        println "${ravi}"
        println "here is my first time calling function2===" + myfunction(10,200)
        println "here is my first time calling function3===" + myfunction(10)
        println "here is my first time calling function4===" + myfunction()
                
          }    
       }  
     }
   }
}
