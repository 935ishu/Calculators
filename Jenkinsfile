pipeline{
  agent any
  stages{
    stage('clone'){
      steps{
        git.branch:'main',url:' ';
      }
    }
    stage('compile'){
      steps{
        sh 'javac Calculator.java'
      }
    }
    stage('build'){
      steps{
        sh 'java calculator 25 5'
      }
    }
    stage('test'){
      steps{
        sh 'java calculator 30 -5
      }
    }
    stage('Deploy'){
      steps{
        echo 'Deployment completed'
      }
    }
  }
}
   
      
      
    
