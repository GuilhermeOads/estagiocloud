pipeline {
  agent any
  stages {
    stage('Ler') {
      steps {
        sh '''ls
cat estagio/querovaga.txt

cd /var/www/html
rm index.html
mv querovaga.txt /var/www/html'''
      }
    }
  }
}