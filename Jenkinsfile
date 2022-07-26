pipeline {
    agent any
    properties([parameters([booleanParam(defaultValue: true, name: 'pbool'), string(defaultValue: 'def string', name: 'pname')])])

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
    }
}
