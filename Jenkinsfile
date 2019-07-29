pnode {
  checkout scm
  docker.withRegistry('https://registry.hub.docker.com' , 'deepalipawade') {
    def customImage = docker.build("deepalipawade/demo")
    customImage.push()
  }
}
