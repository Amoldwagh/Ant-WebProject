pipeline
{
  agent any
  stages{
stage
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
