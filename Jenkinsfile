node {
  docker.withRegistry('https://registry.hub.docker.com', 'DockerHub-b.yousri') {
    
      def liferayImage = docker.image('byousri/liferay-7.0.3-ga4-tomcat')
      stage 'Pull image Docker byousri/liferay-7.0.3-ga4-tomcat'
      liferayImage.pull()
      stage 'Push image Docker byousri/liferay-7.0.3-ga4-tomcat'
      liferayImage.push("latest")

  }
}