pipeline{
 
   agent any
   
   stages{
      
           stage('building the project'){

                         when {
                           branch 'master'
                         }

                         steps{
                           echo 'are you working'
                         }

                         post{

                          always{
                             echo 'archiving artifacts'     
                          }

             }
    
   }
   
 }

}
