pipeline{
    agent any
    stages{
      stage("teste 1"){
        steps{
          echo 'printar pipeline teste'
          sh 'git clone https://github.com/gumm29/Test_integrado_jenkins.git'
          sh 'cd Test_integrado_jenkins'
          sh 'ruby -v'
          sh 'gem install bundler'
          sh 'bundle install --jobs'
        //   sh 'cucumber'
        //   sh 'cd .. Test_integrado_jenkins'
        //   sh 'rm -r Test_integrado_jenkins'
        }
      }
    }
}