pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Pipeline for 5G-IO-BOX started'
            }
        }
        stage('Migration') {
            steps {
                echo 'python .\manage.py makemigrations'
            }
            steps {
                echo 'python .\manage.py migrate'
            }
        }
        stage('Jenkins') {
            steps {
                echo ' j '
            }
        }
    }
}
