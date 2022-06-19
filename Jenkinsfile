node ( 'built-in')

{
    stage('Continuous Download-Master') 
	{
    git 'https://github.com/gntsrinu/JenkinsMultiBranch.git'
	}
    stage('Continuous Build- Master') 
	{
    sh label: '', script: 'mvn package'
	}
}
