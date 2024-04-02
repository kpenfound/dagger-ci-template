pipeline {
  agent { label 'dagger' }

  environment {
    DAGGER_MODULE = "github.com/<foo>/daggerverse/<bar>"
  }
  stages {
    stage("dagger") {
      steps {
        sh '''
            dagger call <args>
        '''
      }
    }
  }
}
