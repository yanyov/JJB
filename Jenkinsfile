pipeline{
  agent{
    labalel 'master'
  }
  stages{
    stage('Build Jenkins Jobs'){
        steps{
          sh 'jenkins-jobs --conf server.ini update .'
        }
    }
  }
}
