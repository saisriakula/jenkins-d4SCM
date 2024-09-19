// Timeout
pipeline {
    agent any
    stages {
        stage ('Timeout Stage'){
            steps {
                timeout(time: 1, unit: SECONDS){
                    echo "Sleeping for 60 seconds"
                    sleep 60
                }  
           }
        }
    }
}
