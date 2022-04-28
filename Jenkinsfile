pipeline {
    agent any
    stages {
        stage('git clone') {
            steps {
              git branch: 'main',url: "https://github.com/Anampakademo/Jenkins.git" 
              sh "ls -ll"
            }
        }
    }
}
