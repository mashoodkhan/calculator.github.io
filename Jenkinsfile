pipeline
{
  agent {
    docker {
      image 'node:14'
    }
  }

  stages 
  {
    stage('Build') {
      echo 'Building Calculator App'
    }
    stage('Test'){
      echo 'Testing Calculator App'
    }
    stage('Deploy'){
      echo 'Deployed'
    }
  }
}
