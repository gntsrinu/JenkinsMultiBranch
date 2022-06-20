node('master') 
{
    stage('Continuous Download-Loans') 
	{
    git 'https://github.com/gntsrinu/JenkinsMultiBranch.git'
	}
    stage('Continuous Build-Loans') 
	{
    sh label: '', script: 'mvn package'
	}
}
