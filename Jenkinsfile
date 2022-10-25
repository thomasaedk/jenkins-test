pipeline {
    agent any

    options {
        sidebarLinks([
            [displayName: 'Side Bar Example 1', iconFileName: '', urlName: 'http://example.com']
            [displayName: 'Side Bar Example 2', iconFileName: '', urlName: 'http://example.com']
        ])
    }

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
    }
}
