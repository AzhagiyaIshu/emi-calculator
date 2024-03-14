pipeline{
  agent any
    tools {
    maven 'maven-3.6.1' 
    }
    stages(){
      stage('Build'){
        steps{
        sh'mvn clean install'
        echo'Building the emi calculator application'
      }
    }
  }
}

