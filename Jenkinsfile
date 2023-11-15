pipeline {
    agent {
        node{
            level = "maven"
        }
    }

    stages {
        stage('clone code') {
            steps {
                git branch: 'main' url: 'https://github.com/Snkdeep/AWS-Traing.git'
            }
        }
    }
}