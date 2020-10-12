pipeline {
  agent any
  stages {
    stage('cmake') {
      steps {
        cmakeBuild(cleanBuild: true, installation: 'inSearchPath', buildDir: 'build', buildType: 'Debug', generator: 'Unix Makefiles', sourceDir: '/')
      }
    }

  }
}