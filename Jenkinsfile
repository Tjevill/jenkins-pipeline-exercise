node {
    stage ('Preperation'){
        echo "whvaaah shira?"

    }
    stage ('Build'){
        echo "whvaaah shira?"
        sh "./gradlew clean test jar"
        echo "Hvorfor funker det ikke???"
    }
    stage ('Result'){
        echo "whvaaah shira?"
        junit "**/build/test-results/test/TEST-*.xml"
    }
}