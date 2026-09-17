pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo 'Build Stage'
                echo 'Build Tool: Maven'
                echo 'Compile and package the application'
            }
        }

        stage('Unit and Integration Tests') {
            steps {
                echo 'Run Unit Tests'
                echo 'Tool: JUnit'
                echo 'Run Integration Tests'
                echo 'Tool: Selenium'
            }
        }

        stage('Code Analysis') {
            steps {
                echo 'Analyse code quality and coding standards'
                echo 'Tool: SonarQube'
            }
        }

        stage('Security Scan') {
            steps {
                echo 'Scan code for security vulnerabilities'
                echo 'Tool: OWASP Dependency Check'
            }
        }

        stage('Deploy to Staging') {
            steps {
                echo 'Deploy application to staging environment'
                echo 'Tool: AWS EC2'
            }
        }

        stage('Integration Tests on Staging') {
            steps {
                echo 'Execute integration tests on staging'
                echo 'Tool: Selenium'
            }
        }

        stage('Deploy to Production') {
            steps {
                echo 'Deploy application to production environment'
                echo 'Tool: AWS EC2'
            }
        }
    }
}
