// retry for multiple attempts
// timeout for time limit enfore
pipeline{
    agents any
    stages{
        stage ('Build'){
            steps{
                echo  "*****Entering Build Block****"
                retry(3){
                    echo "Welcome to D4"
                    error "Tsting the retry block"
                }
                echo "After 3 retrys executed"
            }
        }
    }
}
