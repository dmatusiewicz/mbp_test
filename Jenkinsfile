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
stage('My Conditional Stage') {
    when {
        branch 'master'
    }
    steps {
        echo 'Do that only on master branchi!!!!!!!!!!!!!!!!'
    }
}

    }
}
