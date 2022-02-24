pipeline {
  agent any
  stages {
    stage('Job 3') {
      steps {
        build(job: 'Job3-Pipeline2', propagate: true)
      }
    }

    stage('Job 2') {
      steps {
        build(job: 'Job4-Pipeline2', propagate: true)
      }
    }

  }
}