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
        stage("Done"){
            steps {
                sh "Done"
            }
        }
    }
}