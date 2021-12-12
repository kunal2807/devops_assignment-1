pipeline{
    agent any
    stages {
        stage("git")
        {
            steps{
                git branch: 'main', url: ''
            }
        }
        stage("copy")
        {
            steps{
                sh "cp index.html /var/www/html/"
            }
        }
    }
}
