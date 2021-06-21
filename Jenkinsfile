pipeline {
agent any
stages{
  stage('Build'){
    steps{
    sh '/home/nas/apache-maven-3.5.3/bin/mvn clean install'
    }
  }
  stage('Test'){
    steps{
    sh '/home/nas/apache-maven-3.5.3/bin/mvn test'
    }
  }
}
}
