pipeline {
  agent any

  stages {
<<<<<<< HEAD
    stage('Build Artifact - Maven') {
      steps {
        sh "mvn clean package -DskipTests=true"
        archive 'target/*.jar'
      }
=======
      stage('Build Artifact') {
            steps {
              sh "mvn clean package -DskipTests=true"
              archive 'target/*.jar' //commit
            }
        }   
>>>>>>> 09b01cc41710b9ad7c2b65cb5c9dd459ea44c204
    }

    stage('Unit Tests - JUnit and Jacoco') {
      steps {
        sh "mvn test"
      }
    }
  }
}
