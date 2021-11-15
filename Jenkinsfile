pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                echo 'building app'
                print("Hello world")
                print(50+40)
            }
        }
        stage('test') {
            steps{
                echo 'testing app'
                print(500+450)
                print("TEESTING")
            }
        }
        stage('deploy') {
            steps{
                echo 'deploying app'
            }
        }
            
    }
}
