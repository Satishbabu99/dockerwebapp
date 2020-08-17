node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'docker') {

        def customImage = docker.build("satishvaka001/dockerwebapp-master") 

        /* Push the container to the custom Registry   satishvaka001/dockerwebapp-master
*/
        customImage.push()
    }
}
