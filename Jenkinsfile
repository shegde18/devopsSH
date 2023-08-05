pipeline
{
    agent any
    stages
    {
        stage('Github SCM Checkout')
        {       
            steps
            {
                sh 'echo "Downloading code from github"'
            }
        }

        stage('Execute unit test cases')
        {
            steps
            {
                sh 'echo "executing unit test"'
            }
        }

        stage('Code Build')
        {
            steps
            {
                sh 'echo "Building the code"'
            }
        }
    }
}
