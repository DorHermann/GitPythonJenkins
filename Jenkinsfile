pipeline {
    agent any

        stage('Run Python Script') {
            steps {
                script {
                    // Run your Python script
                    bat 'C:\\Users\\dor.h\\AppData\\Local\\Programs\\Python\\Python312\\python.exe HelloWord.py'
                }
            }
        }


    post {
        success {
            echo 'Python script ran successfully!'
        }
        failure {
            echo 'Python script failed!'
        }
    }
}
