pipeline{
    agent any
    stages{
        stage('Build'){
            when{
                changeset pattern:"*.js"
            }
            steps{
               echo "changeset build done"
            }
        }
    }
}
