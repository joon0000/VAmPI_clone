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
                checkmarxASTScanner additionalOptions: '', baseAuthUrl: '', branchName: ' ${GIT_BRANCH},', checkmarxInstallation: 'Checkmarx_CLI', credentialsId: '', projectName: 'VAmPI', serverUrl: '', tenantName: '', useOwnAdditionalOptions: true
            }
        }
    }
}