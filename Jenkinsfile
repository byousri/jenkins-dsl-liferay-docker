node {
    def liferayImage = docker.image('byousri/liferay:7.0.3-ga4-tomcat')
    docker.withRegistry('https://registry.hub.docker.com', 'DockerHub-b.yousri') {
            liferayImage.push("${env.BUILD_NUMBER}")
            liferayImage.push("latest")
    }
}