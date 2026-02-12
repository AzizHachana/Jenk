pipeline {

 agent any


 stages {

 stage('GIT') {

           steps {

               git branch: 'main',

               url: 'https://github.com/AzizHachana/Jenk.git'

          }

     }

 stage ('Compile Stage') {

 steps {

 sh 'mvn clean compile'

 }

 }

 }

}
