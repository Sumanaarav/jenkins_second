pipeline{
    agent{
        label 'Slave1'
    }

    stages{
        stage('Build')  {
            steps{
                sh 'sleep 5'

            }
        }

        stage('Test')  {
            steps{
                sh '''
                    #!bin/bash
                    ls -lrt
                    sleep 5
                ''' 

                
            }
        }

    }
}
    