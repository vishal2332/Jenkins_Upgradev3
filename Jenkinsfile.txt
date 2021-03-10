pipeline {
      agent any
      stages {
           stage('Init') {
                 steps {
                     echo 'Hi this is vishal learning jenkins codepipeline'
                     echo 'i am writing this jenkins file manually'
                 }
           }
      }


}