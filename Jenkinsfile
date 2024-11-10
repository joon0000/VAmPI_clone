pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Checkmarx') {
            steps {
                checkmarxASTScanner additionalOptions: '', baseAuthUrl: '', branchName: '', checkmarxInstallation: 'Checkmarx_CLI', credentialsId: '', projectName: 'VAmPI2', serverUrl: '', tenantName: '', useOwnAdditionalOptions: true
            }
        }
    }
}