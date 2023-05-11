pipeline {
    agent any

    stages {
        stage('Trigger Job') {
            steps {
                build job: 'helm-deploy-pipeline',parameters:[
                    string(name: 'build', value: 'Value 1')
                ]
                
               
            }
        }
    }
}