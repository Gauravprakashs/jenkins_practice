pipeline{
    agent any

    stages{
        stage("get"){
            steps{
                git branch: 'master',
                url: 'https://github.com/Gauravprakashs/jenkins_practice.git'
            }
        }
        stage("run"){
            steps{
                echo "Runnig "
                sh 'python3 hello.py'
            }
        }
        stage("Exiting"){
            steps{
                echo "Exiting ....."
            }
        }
    }
}
