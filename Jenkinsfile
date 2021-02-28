node {
  stage('SCM checkout')
  {
    git 'https://github.com/mukulbhardwaj10/maven-hello-world/new/master'
  }
  stage('Compile-package')
  {
    sh 'mvn package'
  }
}
