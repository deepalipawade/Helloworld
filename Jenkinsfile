node {
  checkout scm
  docker.withRegistry('https://registry.hub.docker.com' , 'img') {
    def customImage = docker.build("deepalipawade/demo")
    customImage.push()
  }
}
