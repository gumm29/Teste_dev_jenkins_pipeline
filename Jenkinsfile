pipeline{
  agent any
  stages{
    stage("Teste Integrados"){
      steps{
        sh 'rm -r <Test_integrado_jenkins>'
        sh 'git clone <https://github.com/gumm29/Test_integrado_jenkins.git>'
        sh 'gem install bundler'
        sh 'cd <Test_integrado_jenkins> pwd bundle install cucumber -p regressivo || cucumber @rerun.txt -p headless --retry 2'
      }
    }
  }
}