pipeline{
  agent{
  label "slave"
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
