pipeline {
    agent none
    stages {
        stage ('Example') {
            steps {
                // log.info 'Starting' 
                script { 
                    assumeRole()
                    echo 'Branch name ' + env.BRANCH_NAME

                }
            }
        }
    }
}
