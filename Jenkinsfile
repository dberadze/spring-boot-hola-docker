pipeline {
  agent {
    dockerfile {
      filename 'Dockerfile'
    }

  }
  stages {
    stage('git pull') {
      steps {
        git(url: 'https://github.com/dberadze/spring-boot-hola-docker', branch: 'master')
      }
    }

  }
}