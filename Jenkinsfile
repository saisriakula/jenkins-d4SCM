// Script:
//pipeline > stages > stage >setps > script
// It allows us to write our custorm ccode in groovy
pipeline {
    agent {
        label 'java-agent-slave'
    }
    stages {
        stage ('Build') {
            steps {
                echo "This is the stage for Building MVN app"-i
                //linux commands
                sh 'hostname '
            }
        }
        stage ('ScriptedStage') {
            steps {
                echo "Executing Scripted Stage"
                // Write some Custom Code
                script {
                    // Defining a variable
                    def course = "k8s"
                    if (course == "k8s") {
                        println("Thanks for enrolling into $course")
                    }
                    else
                        println("Do learn k8s")
                    }
                    sleep 10
            }
        }
    }
}
