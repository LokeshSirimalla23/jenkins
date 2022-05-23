properties([parameters([choice(choices: ['yes', 'No'], name: 'state')]), pipelineTriggers([pollSCM('* * * * * ')])])
pipeline {
  agent any
    stages {
      stage('gitcheckout') {
        steps {
           git branch: 'main', url: 'https://github.com/LokeshSirimalla23/jenkins.git'
           bat 'echo \'git checkout poll scm\''
          }
       }
    }
}
