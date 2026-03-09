pipeline{
  agent any
  stages{
    stage('Clone'){
      steps{
        git url:'https://github.com/manasvi-a/Jenkins-';
        branch:'main'
      }
    }
    stage('Run script'){
      steps{
        sh 'chmod +x Script.sh'
        sh './Script.sh'
      }
    }
  }
}
