pipeline{
    agent any
    stages{
      stage("teste 1"){
        steps{
          echo 'printar pipeline teste'
          sh 'git clone https://github.com/gumm29/Test_integrado_jenkins.git'
          sh 'ruby -v'
          sh 'bundle install'
          sh 'start index.html'
        }
      }
    }
}