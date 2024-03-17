pipeline{
  agent any
    tools {
    maven 'maven-3.6.1' 
    }
    stages(){
      stage('Build'){
        steps{
        bat'mvn clean install'
        echo'Building the emi calculator application'
      }
      }     
        stage('Test'){
           steps{
             echo'Tetsing the application'
           }
    }
  }
}

