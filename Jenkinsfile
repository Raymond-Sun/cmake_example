pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        cmake(installation: 'InSearchPath', arguments: 'cmake arguments: \'-DCMAKE_TOOLCHAIN_FILE=~/Projects/vcpkg/scripts/buildsystems/vcpkg.cmake\', installation: \'InSearchPath\'                 cmakeBuild buildType: \'Release\', cleanBuild: true, installation: \'InSearchPath\', steps: [[withCmake: true]]')
      }
    }

  }
}