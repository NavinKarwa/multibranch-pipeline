pipeline {
  agent any 
  stages{
       stage('Compile') {
           steps{
              sh 'gcc -o prg1 prg1.c'
              echo 'file compiled successfully'
           }
       }
       stage('RUN') {
          steps{
             sh './prg1'
             echo 'file run successfully'
          }
       }
  }
}
