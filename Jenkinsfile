pipeline {
  agent any
  stages {
    stage('Job 1') {
      steps {
        build(job: ' Job1-Pipeline1', propagate: true)
      }
    }

    stage('Job 2') {
      steps {
        build(job: 'Job2-Pipeline1', propagate: true)
      }
    }

  }
}