pipeline{
 agent any
   stages {
     stage ('Build'){
       steps{
         echo ' Running buils automation'
         sh './gradlew build --no-daemon'
         archiveArtifacts artifacts: 'dist/trainScheduler.zip'
       }
     }
   }

}
