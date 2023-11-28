pipeline
{
agent any //this is my agent selection
stages{
   stage("Stage1"){
     steps{
      script{
	    var1 = 10
		ravi = "Raveender Nenavath"
			println "Hello here is your variable value : ${var1}"
			println "Hello here is your variable value : ${ravi}"
			println "Hello here is your predifined variable : ${BRANCH_NAME}"
			println "Hello here is your predifined variable : ${BUILD_NUMBER}"
			println "Hello here is your predifined variable : ${JOB_NAME}"
			println "Hello here is your predifined variable : ${JENKINS_HOME}"
			println "Hello here is your predifined variable : ${WORKSPACE}"

        }
       }
     }

   }
}
