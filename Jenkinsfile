pipeline{
    agent any
    stages {
        stage("git")
        {
            steps{
                git branch: 'main', url: 'https://github.com/kunal2807/devops_assignment-1'
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
