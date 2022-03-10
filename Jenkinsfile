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
                echo 'python manage.py makemigrations'
                echo 'python manage.py migrate'
            }
        }
       stage('Run Server') {
            steps {
                echo 'python ./manage.py runserver'
                echo 'cd frontend'
                echo 'npm run dev'
            }
        }
        stage('Jenkins') {
            steps {
                echo ' j '
            }
        }
    }
}
