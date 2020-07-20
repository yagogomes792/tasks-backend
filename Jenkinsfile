pipeline {
    agent any
    stages('Build Backend') {
        stage {
            steps {
                bat 'mvn clean package -DskipTests=true'
            }
        }
    }
}