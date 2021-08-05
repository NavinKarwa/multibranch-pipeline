pipeline {
  agent any 
  stages{
       stage('Compile') {
           sh 'gcc -o prg1 prg1.c'
           echo 'file compiled successfully'
       }
       stage('RUN') {
           sh './prg1'
           echo 'file run successfully'
       }
  }
}
