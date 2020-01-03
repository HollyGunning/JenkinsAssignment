Jenkinsfile (Declarative Pipeline)
pipeline 
{
    agent any
    stages 
    {
        stage('Fetch')
        {
            steps
            {
                git url:'https://github.com/HollyGunning/JenkinsAssignment'
            }
        }

        stage('Build') {
            steps {
                sh 'npm --version'
            }
        }
    }
}