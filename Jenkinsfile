pipeline{
 
   agent any
   
   stages{
    
    
    
          stage('sanity stage'){
          
           steps{
                sh 'echo  "Hello Jenkins Pipeline"'
                sh 'ls -al'
                sh 'pwd'
                sh 'echo "show me user/bin"'
                sh 'ls -al /usr/bin'
                sh 'whoami'
                sh 'npm -v'
           
                sh 'node -v'
           
           }
          }
    
      
           stage('building the project'){

                        /* when {
                           branch 'master'
                         }*/

                         steps{
                           echo 'BUILDING PROJECT'
                           sh './gradlew build'
                         }

                         post{

                          always{
                             echo 'archiving artifacts'     
                          }

             }
    
   }
   
 }

}
