pipeline {
  agent any
    stages {
      stage('gitcheckout') {
        steps {
           git branch: 'main', url: 'https://github.com/LokeshSirimalla23/jenkins.git'
           sh '''
           echo "gitcheckout"
           '''
          }
       }
    }
}
