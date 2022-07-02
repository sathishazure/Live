node{
  
tools{
  jdk 'myjava'
  mvn 'mymaven'
  }

  stage('git stage'){
   
    git 'https://github.com/kliakos/sparkjava-war-example.git'
    }

  stage('mvn apcage stage'){

       sh 'mvn package'
   }

  stage('copy stage'){

   echo ("copy stage")

   }



}
