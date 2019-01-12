pipeline{
 
   agent any
   
   stages{
    
    
    
          stage('sanity stage'){
          
           steps{
           
           
               node -v
           
           }
          }
    
      
           stage('building the project'){

                        /* when {
                           branch 'master'
                         }*/

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
