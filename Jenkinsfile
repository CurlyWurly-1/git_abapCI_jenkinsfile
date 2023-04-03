pipeline {
    agent any
    stages {
        stage('test A4H') {
            steps {
                abapCi sapPackagename: 'Z_TEST_GIT', runUnitTests: (true), runAtcChecks: (true), withCoverage: (true), sapSystemLabel: 'A4H'
            }
        }
    }
}
