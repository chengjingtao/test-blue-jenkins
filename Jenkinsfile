pipeline {
    agent any
    node() {
    stage "clone"
    git 'https://github.com/chengjingtao/LoveFavorites.git'
   stage 'build'
   sh "pwd"
    sh "ls -l"
   input "beging to build now !!!!??"
   sh "echo this is build"
   stage 'deploy'
   sh 'echo this is deploy'
   }
 
}

