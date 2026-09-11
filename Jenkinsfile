pipeline{
     agent any

    stages {
      stage('build') {
          step {
            echo 'Build completed successfully'
       }
   }
        stage('test') {
              steps {
              echo 'test passed sucessfully'
         }
    }
     stage('Archive Artifacts') {
          steps {
               archiveArtifacts artifacts: 'build.txt'
          }
     }
    stage('Deploy') {
           steps {
               echo 'Deployment completed successfully'
           }
    }
    }
