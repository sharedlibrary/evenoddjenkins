@Library('my-shared-library') _

//evenOrOdd(currentBuild.getNumber())
//log.info 'Starting'
//log.warning 'Nothing to do!'
pipeline {
    agent any
    stages {
        stage('Git Checkout') {
            steps {
            gitCheckout(
                branch: "dev",
                url: "https://github.com/mahatab16/mavenrepo.git"
            )
            }
    }
    }
}


