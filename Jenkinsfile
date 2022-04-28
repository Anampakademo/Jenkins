pipeline {
    agent any
    stages {
        stage('git clone') {
            steps {
              git branch: 'main',url: "https://github.com/Anampakademo/Apache_ansible.git" 
              sh "ls -ll"
            }
        }
    }
}
