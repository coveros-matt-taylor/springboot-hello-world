
node {
    stage('Checkout') {
        echo 'Checkout....'
        checkout scm
    }
    stage('Build') {
        // sh './gradlew build && java -jar build/libs/gs-spring-boot-0.1.0.jar'
        echo 'Building....'
        sh 'sudo ./gradlew --version'
    }
    stage('Test') {
        echo 'Building....'
    }
    stage('Deploy') {
        echo 'Deploying....'
    }
}
