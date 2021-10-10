pipeline{
  agent{
  label "slave1"
  }
  tools {nodejs "Node"}
  stages {
   stage ('build'){
     steps{
         sh 'npm install'
         sh 'npm pack'
         sh "weleecome to jenkins"
      }
    }
 }
}
