@Library('library')_

pipeline
{
    agent any
    stages
    {
        stage('contdown_Loans')
        {
            steps
            {
                script
                {
                    cicd.gitdownload("maven1")
                }
            }
        }
         stage('contbuild_Loans')
        {
            steps
            {
                script
                {
                    cicd.build()
                }
            }
        }
    }
}
         
