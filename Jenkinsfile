pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'hostname'
		sh 'ip addr show'
		sh 'cat /etc/resolv.conf '
            }
        }
    }
}
