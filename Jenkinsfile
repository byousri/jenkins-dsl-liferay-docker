node {
    def liferayImage = docker.image('byousri/liferay:7.0.3-ga4-tomcat')
    liferayImage.push("${env.BUILD_NUMBER}")
    liferayImage.push("latest")
}