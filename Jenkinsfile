pipeline {
    agent any
    tools{
        nodejs "NodeJs"
    }

    stages {
        stage("checkout"){
            steps{
                checkout scm
            }
        }
        // stage{"Install"}{
        //     steps{
        //         bat "npm install"
        //     }
        // }
        // stage{"build"}{
        //     steps{
        //         bat "npm run build"
        //     }
        // }
        // stage{" Test"}{
        //     steps{
        //         bat "npm test"
        //     }
        // }
        stage ("Execute"){
            steps{
                bat "node first.js"
            }
        }
    }
}
