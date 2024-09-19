pipeline{
    agent any
    tools {
        maven "MAVEN_PATH"
    }
    stages {
        stage ('Maven') {
            steps {
                echo "*****Maven Version with default java*****"
                sh 'mvn --version'
            }
        }
    stages {
        stage ('Maven') {
            steps {
                tools {
                    jdk 'jdk-17'
                }
                echo "*****Maven Version with my custom java /opt*****"
                sh 'mvn --version'
            }
        }
    }
}
