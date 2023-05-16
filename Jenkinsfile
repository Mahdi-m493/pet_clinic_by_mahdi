pipeline {
  agent {
    docker {
      image 'jenkins/agent:alpine-jdk11'
    }

  }
  stages {
    stage('error') {
      steps {
        git(url: 'https://github.com/Mahdi-m493/pet_clinic_by_mahdi', branch: 'main')
      }
    }

  }
}