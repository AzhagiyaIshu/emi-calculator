pipeline
{
tools
{
    maven 'maven-3.6.1'
}
  agent any 
       {
          stages("Build") {
            steps {
                      sh 'mvn clean install'
                      echo 'Building the emi calculator application'
                  }
         }
     }
}
                  
         
