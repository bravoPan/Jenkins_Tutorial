pipeline {
    agent any
    triggers {
        pollSCM('* * * * *')
    }
    stages {
        stage("Unit test") {
            steps {
                sh "python3 test_calculator.py"
            }
        }
    }
}