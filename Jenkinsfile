pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        cmake(installation: 'InSearchPath', arguments: '-DCMAKE_TOOLCHAIN_FILE=/usr/share/cmake/Modules/Compiler/GNU-C.cmake\', installation: \'InSearchPath\'                 cmakeBuild buildType: \'Release\', cleanBuild: true, installation: \'InSearchPath\', steps: [[withCmake: true]]')
      }
    }

  }
}
