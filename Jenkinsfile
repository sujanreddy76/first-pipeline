//This pipeline is a Declarative pipeline
pipeline {
    agent any
    stages {
        stage('Build') {
          steps {
              echo "Building the application, Sujan has done some changes"
             // sh "mvn package -Dskip.tests=true"
          }
        }
        stage('Sonar') {
            steps {
                echo "Executing Sonar"
                //sh "mvn sonar:sonar"
            }
        }
        stage('DockerBuild') {
            steps {
                echo "Building docker image"
               // sh "docker build -t xyz ."
            }
        }

    }
}
