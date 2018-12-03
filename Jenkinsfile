pipeline {
  agent {
      docker('gradle')
   }
   stages {
       stage('Build') {
           steps {
               sh 'gradle hello'
           }
       }
   }
}
