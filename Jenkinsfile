node('built-in') 
{
    stage('Continuous Download') 
	{
    git 'https://github.com/Bhagavan094/maven.git'
	}
    stage('Continuous Build') 
	{
    sh label: '', script: 'mvn package'
	}
}
