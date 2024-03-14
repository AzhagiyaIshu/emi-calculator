pipeline{
  agent any
    stages(){
      stage('Build'){
        steps{
        sh'mvn clean install'
        echo'Building the emi calculator application'
      }
    }
  }
}

