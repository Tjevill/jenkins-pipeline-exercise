pipeline {
    
    agent any

    stages{
        stage ('Preperation'){
            echo "whvaaah shira?"

        }
        stage ('Build'){
            echo "whvaaah shira?"
            sh "./gradlew clean test jar"
            echo "Hvorfor funker det ikke???"
        }
        stage ('Result'){
            echo "Added junit result. Still not automatic..."
            junit "**/build/test-results/test/TEST-*.xml"
        }
    }
}