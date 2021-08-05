pipeline {
  agent any 
  stages{
       stage('Compile') {
            sh 'gcc -o prg1 prg1.c'
       }
       stage('RUN') {
           sh './prg1'
       }
  }
}
