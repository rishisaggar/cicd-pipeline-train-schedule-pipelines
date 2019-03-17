pipeline {
  agent any
  stages {
    stage('Build')
    echo 'Running build auotmation'
    sh './gradelw build --no-daemon'
    archiveArtifacts artifacts: 'dist/trainSchedule.zip'
    }
   }
  } 
}
