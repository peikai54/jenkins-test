pipeline {
  agent any
  tools {nodejs "node"}
 
  stages {
    stage('Example') {
      steps {
        sh 'npm config ls'
        sh '''
            node -v
            npm -v
            gulp -v
            hexo -v
        '''
      }
    }
  }
}
