pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'YIPEEEEEEEEEEEEEEEEEEEEEEE'
                sh 'echo "YIPEEEEEEEEEEEE, Dmitri" > hello.txt'
                sh 'cat hello.txt'
            }
        }
    }
stages {
        stage('Run app') {
            steps {
		sh 'node.js'
            }
        }
    }

}
