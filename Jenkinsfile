pipeline{
 agent any
   stages {
     stage{
       steps{
         echo ' Running buils automation'
         sh './gradelw build --no-daemon'
         archiveArtifacts artifacts: 'dist/trainScheduler.zip'
       }
     }
   }

}
