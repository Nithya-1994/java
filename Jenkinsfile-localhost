pipeline {
    agent any

    stages {
        stage('git-clone') {
            steps {
                git 'https://github.com/Nithya-1994/java.git'
            }
        }
        stage('java-project') {
            steps {
                bat '''javac Test.java
                java Test.java'''
            }
        }
    }
}
