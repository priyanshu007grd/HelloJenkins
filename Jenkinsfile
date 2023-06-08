pipeline {
    agent any
    stages {
        stage("Build"){
            steps {
                dir("./") {
                    sh "mvn clean install"
                }
            }
        }
        stage("Test"){
            steps {
                dir("./") {
                    sh "mvn test"
                }
            }
        }
        stage("Done1"){
            steps {
                sh "Done1"
            }
        }
        stage("Done2"){
            steps {
                sh "Done2"
            }
        }
    }
}