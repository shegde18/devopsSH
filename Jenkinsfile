pipeline
{
    agent any
    stages
    {
        stage('display hello')
        {       
            steps
            {
                sh 'echo "Hi Jenkins"'
            }
        }

        stage('build')
        {
            steps
            {
                sh 'echo "executing unit test"'
            }
        }

        stage('test')
        {
            steps
            {
                sh 'echo "Testing the code"'
            }
        }
    }
}
