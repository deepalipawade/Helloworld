node {
  checkout scm
  docker.withRegistry('https://registry.hub.docker.com' , 'mypipeline') {
    def customImage = docker.build("depalipawade/demo")
    customImage.push()
  }
}
