pnode {
  checkout scm
  docker.withRegistry('https://registry.hub.docker.com' , 'root') {
    def customImage = docker.build("deepalipawade/demo")
    customImage.push()
  }
}
