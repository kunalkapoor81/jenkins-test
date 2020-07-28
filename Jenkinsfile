pipeline{
       agent any
       stages {
              stage("run frontend") {
                  steps {
                        echo "executing npm..."
                         nodejs('nodejs-14.6') {
                                  sh 'npm install'
                         }
                        }
                   }
              stage("run backend") {
                  steps {
                        echo "executing npm - BIG CHANGE..."
                        }
                   }
                }
          }
