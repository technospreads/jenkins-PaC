pipeline 
{
agent any
stages{
   stage("Working with Loops"){
     steps{
      script{
            File obj = new File("/tmp/ravi.txt")
            
            println "Here is my file content ==== ${obj.text}" 
            println "Here is my read line content=== ${obj.readLines()}"
                  
          }    
       }  
     }
   }
}
