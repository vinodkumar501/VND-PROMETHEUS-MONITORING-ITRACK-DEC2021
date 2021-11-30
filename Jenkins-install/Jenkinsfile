pipeline {                       //must be top level
   agent any                     //agent -> where to execute like jenkinscluster , windows node like
   stages {
     stage("build") {
       steps {
         //sh 'npm install'      //if you run java based appn use npm 
         //sh 'npm build'
         echo 'build appication'
       }
     }
     stage("test") {
       steps {
         echo 'test appication'
       }
     }
     stage("deploy") {
       steps {
         echo 'deploy appication'       
       }
     }
  }
}
