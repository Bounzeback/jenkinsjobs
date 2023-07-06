pipeline{
    agent any
        stages {
        stage('Build') {
            steps {
               checkout scmGit(branches: [[name: '*/job1']], extensions: [], userRemoteConfigs: [[credentialsId: 'e985edd7-67a2-4153-97aa-8c2c4e52f7ae', url: 'https://github.com/Bounzeback/jenkinsjobs.git']])
            }
        }
        stages{
        stage('1-member1'){
            steps{
                 'echo "ifeanyi"'
            }
        }
        stage('2-member2'){
            steps{
                'echo "Marius"' 
            }
        }
        stage('3-member3'){
            steps{
                'echo "Kingsley"'
            }
        }
        stage('4-member'){
            steps{
                'echo "Ronald"'
            }
        }
    }
}
