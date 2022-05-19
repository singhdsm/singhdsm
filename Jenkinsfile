pipeline {                                                                                                         
       agent any                                                                                                 
       
       stages {                                                                                                                                                                                       

               stage("build") {

                       steps {                                                                                      
                               echo ' Building the application …'
                       }
                }

               stage("test") {

                       steps {
                               echo ' Testing the application …'
                       }
                }

               stage("build") {

                       steps {
                               echo ' Deploying the application …'
                       }
                }

        }
}
