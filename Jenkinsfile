node {
    stage('git-clone') { 
        git 'https://github.com/Nithya-1994/java.git'
    }
    stage('java-commands') {
        sh '''javac Test.java
        java Test.java'''
    }
}
