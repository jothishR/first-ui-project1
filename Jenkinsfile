pipeline {
    agent {
        docker {
            image "python:3.6"
        }
    }
    stages {
        stage("Build") {
            steps { 
                sh "git clone https://github.com/jothishR/first-ui-project1.git;cd first-ui-project1/;pwd"
            }
        }
    }
}
