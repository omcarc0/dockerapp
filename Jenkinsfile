node {
    checkout scm

    docker.withRegistry('https://https://registry.hub.docker.com/', 'dockerHub') {

        def customImage = docker.build("omar/dockewebapp")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}