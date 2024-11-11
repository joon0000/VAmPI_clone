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
                checkmarxASTScanner additionalOptions: '--project-groups Internship', baseAuthUrl: '', branchName: '', checkmarxInstallation: 'Checkmarx_CLI', credentialsId: '', projectName: 'VAmPI', serverUrl: '', tenantName: '', useOwnAdditionalOptions: true
            }
        }
    }
}