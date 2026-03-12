pipeline {
    agent any

    stages {
        stage('Lab 1 Practice') {
            steps {
                echo 'This is Lab 1 work'
                sh '''
                mkdir build
                touch build/computer.txt
                echo "Mainboard" >> build/computer.txt
                echo "Display" >> build/computer.txt
                grep "Display" build/computer.txt
                '''
            }
        }
    }
}
