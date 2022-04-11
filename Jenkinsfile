node('master')
{
    stage('ContinuousDownload_loans')
        {
    git 'https://github.com/sunildevops78/maven.git'
        }
    stage('ContinuousBuild_loans')
        {
    sh label: '', script: 'mvn package'
        }

}

