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
                bat 'javac -cp junit-4.13.jar; Student.java studentTest.java'
            }
        }
    }
}