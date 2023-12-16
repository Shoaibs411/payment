pipeline{
    agent {
        label "ws"
    }
    stages{
        stage('Lint Checks'){
            steps{
                sh "echo ***** Starting Style Checks ***** "
                //sh "/home/centos/payment/pylint payment.py || true"
                //sh "/home/centos/payment/pylint rabbitmq.py || true"
                sh "/home/centos/payment/pylint *.py || true"
                sh "echo ***** Style Checks are completed ***** "

            }
        }
        stage('Static Code Analysis'){
            steps{
                sh "echo ***** Starting Static Code Analysis ***** "

            }
        }
    }
}