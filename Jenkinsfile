pipeline{
    agent any
    tools {
        maven "MAVEN_PATH"
    }
    stages {
        stage ('Maven') {
            steps {
                echo "*****Maven Version*****"
                sh 'mvn --version'
            }
        }
    }
}
