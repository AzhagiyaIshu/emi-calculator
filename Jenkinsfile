pipeline{
  tools{
    maven'maven-3.6.1'
  }agentany{
    stages("Build"){
      steps{
        sh'mvn clean install'echo'Building the emi calculator application'
      }
    }
  }
}
