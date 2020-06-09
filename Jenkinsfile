pipeline{
    agent any
    stages{
      stage("teste 1"){
        steps{
          echo 'printar pipeline teste'
          sh 'git clone https://github.com/gumm29/Test_integrado_jenkins.git'
          sh 'ruby -v'
          sh 'gem install bundler'
          sh 'bundle install'
          sh 'cucumber'
        }
      }
    }
}