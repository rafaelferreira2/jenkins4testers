pipeline {
   agent {
      docker {
         image "ruby"
      }
   }
   stages {
      stage("Build") {
         steps {
           sh "bundle install"
         }
      }
      stage("Tests"){
          steps {
            sh "echo 'simulando testes automatizados' "
          }
      }
   }
}