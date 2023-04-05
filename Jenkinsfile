pipeline {
    agent any
    stages {
        stage('test A4H') {
            steps {
                abapCi abapPackagename: 'Z_GIT', runUnitTests: (true), runAtcChecks: (true), withCoverage: (true), sapSystemLabel: 'A4H'
            }
        }
    }
}
