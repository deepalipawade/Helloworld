node {
  checkout scm
  docker.withRegistry('https://registry.hub.docker.com' , 'root') {
    def customImage = docker.build("depalipawade/demo")
    customImage.push()
  }
}
