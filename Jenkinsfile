pipeline {

 agent any

 tools {
  jdk 'JAVA_HOME'
  maven 'M2_HOME'
 }

 stages {

 stage('GIT') {

           steps {

               git branch: 'main',

               url: ' https://github.com/zied-fad/testfoyer.git'

          }

     }

 stage ('clean Stage') {

 steps {

 sh 'mvn clean '

 }

 }
  stage ('Compile Stage') {

 steps {

 sh 'mvn clean compile'

 }

 }

 }

}
