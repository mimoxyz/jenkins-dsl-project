 node('openshift') {
  stage 'Build and Test'
  env.PATH = "${tool 'Maven 3'}/bin:${env.PATH}"
  sh 'echo \"Hello World!\"'
 }