pipeline {

 agent any

 tools {
  jdk 'JAVA_HOME'
  maven 'M2_HOME'
 }

 stages {

               git branch: 'main',

               url: ' https://github.com/zied-fad/testfoyer.git'

          }

     }

 stage ('clean Stage') {

 
  stage ('Compile Stage') {

 steps {

 sh 'mvn clean compile'

 }

 }

 }

}
