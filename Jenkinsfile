pipeline 
{
agent any //this is my agent selection
stages{
   stage("Working with Loops"){
     steps{
      script{
            File obj = new File("/tmp/ravi.txt")
            obj.write("This is my PaC inside test code\n")
            obj.append("This is my Jenkin-Pac-test-case\n")
            obj.append("This is my Jenkin-Pac-test-case2\n")
            obj.append("This is my Jenkin-Pac-test-case3\n")
            obj.append("This is my Jenkin-Pac-test-case4\n")
            println "Here is my file content ==== ${obj.text}" 
            println "Here is my read line content=== ${obj.readLines()}"
                  
          }    
       }  
     }
   }
}
