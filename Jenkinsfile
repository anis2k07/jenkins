node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'dockerHub') {

        def customImage = docker.build("anis2k07/jenkins")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
