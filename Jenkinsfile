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
        stage('Run app') {
            steps {
		sh 'node server.js'
            }
        }

}
}
