pipeline{
    agent any
    stages{
        stage("Excute playbook"){
            steps{
                ansiblePlaybook credentialsId: '82475e25-d4b9-4d81-be6b-482268628d89', disableHostKeyChecking: true, installation: 'root', inventory: '/opt/playbook/inventory', playbook: '/opt/playbook/java.yml', vaultTmpPath: ''
            }
        }
    }
}
