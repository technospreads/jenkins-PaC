pipeline 
{
agent any //this is my agent selection
stages{
   stage("Working with Loops"){
     steps{
      script{
         /*
         this is my line one comment
         this is my line 2 comment 
         final
         */
            File obj = new File("/tmp/ravi.txt")
            obj.write("This is my PaC inside test code\n")
            obj.append("This is my Jenkin-Pac-test-case\n")
            obj.append("This is my Jenkin-Pac-test-case2\n")
            obj.append("This is my Jenkin-Pac-test-case3\n")
            obj.append("This is my Jenkin-Pac-test-case4\n")
            println "Here is my file content ==== ${obj.text}" 
            for (line in obj.readLines() ){
               println "Here is my read line content=== ${line}"
            }      
          }    
       }  
     }
   }
}
