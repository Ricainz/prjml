Pipeline{
  agent any
  stages{
    stage('Build'){
      steps{
        echo 'Building Docker Images'
        bat build.bat
      }
    }
    stage('Running'){
      steps{
        echo 'running flask app'
        bat run.bat
      }
    }
  }
}
