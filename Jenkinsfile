pipeline {
        agent any {
        stage ('Build') {
              steps {
              echo 'running build automation'
              sh './gradlew build --nodeamon'
              archiveArtifacts artifacts: 'dist/trainSchedule.zip'
              }
        }
        }
   }
           
