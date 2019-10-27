pipeline {
        agent any 
        stages {
          stages('Build'){
            steps {
                echo 'running build automation'
                sh './gradlew build --no-daemon'
                archiveArtifacts artifacts:'dist/trainSchedule.zip'
                 }
               }
            }
          }    
