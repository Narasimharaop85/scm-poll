pipeline{
    agent any
    stages{
        stage("build")
        {
            steps{
                sh 'echo "hai padmajanaveen"'
            }
        }
        stage('BuildMore')
        {
            steps
            {
                
                sh '''
                echo "multi shell steps work"
                ls -l
                '''
            }
        }
        stage('fibonacciSeries')
        {
            steps
            {
                
                sh '/root/.jenkins/scripts/fibo.sh'
            }
        }
    }
}
