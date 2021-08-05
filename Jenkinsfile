pipeline {
  agent any 
  stages{
       stage('Compile') {
           steps{
              sh 'gcc -o prg1 prg1.c'
           }
       }
       stage('RUN') {
          steps {
           sh './prg1'
         }
       }
  }
}
