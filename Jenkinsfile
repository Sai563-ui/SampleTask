pipeline
{
agent any
stages
{

stage('Build')
{
steps{
bat "mvn clean"
}
}
stage('deploy')
{
steps{
echo 'deploying the code'
}
}

stage('test')
{
steps{
bat "mvn test -P Task1"
}
}

stage('release')
{
steps{
echo 'The code is release'
}
}

}
}