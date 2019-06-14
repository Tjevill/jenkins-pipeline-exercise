pipeline {
    
    agent any

    stages{
        stage ('Preperation'){
            echo "stage Preperation"

        }
        stage ('Build'){
            echo "stage Build"
            sh './gradlew clean test jar'
        }
        stage ('Result'){
            echo "stage Result"
            junit "**/build/test-results/test/TEST-*.xml"
        }
    }
}