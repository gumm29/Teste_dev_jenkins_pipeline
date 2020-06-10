pipeline{
  agent any
  stages{
    stage("dev"){
      steps{
        echo 'printar pipeline teste'
        sh 'rm -r Test_integrado_jenkins'
        sh 'git clone https://github.com/gumm29/Test_integrado_jenkins.git'
        sh 'gem install bundler'
        sh 'cd Test_integrado_jenkins && pwd && bundle install && cucumber -p headless'
      }
    }
  }
}