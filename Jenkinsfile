pipeline{
 
   agent any
   
   stages{
    
    
    
          stage('sanity stage'){
          
           steps{
           
           
                echo  "Hello Jenkins Pipeline"
                ls -al
                pwd
                echo "show me user/bin"
                ls -al /usr/bin
                whoami
                npm -v
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
