node ('debian-docker') {
  stage 'Checkout'
  checkout scm

  stage 'Build'
  def image = docker.build('kiall/jenkins-master:snapshot', '.')
}
