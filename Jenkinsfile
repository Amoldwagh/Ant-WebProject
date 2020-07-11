pipeline
{
  agent any
  stages  {
stage('deploy-code')
{
steps
  {
    withAnt(installation: 'localant', jdk: 'localjdk') {
      sh 'ant -f build.xml -v'
}
    
  }
}
}
}
