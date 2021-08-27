pipeline {
    agent any
    parameters { 
        string(name: 'CLUSTER_IP', defaultValue: 'staging', description: 'K8S Test Cluster IP') 
        string(name: 'PR_BRANCH', defaultValue: 'staging', description: 'Branch you want to test with') 
    }
    
    stages {
        stage('build') {
            steps {
                echo 'hello world'
            }
        }
    }
}
