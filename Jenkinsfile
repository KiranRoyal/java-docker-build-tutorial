node {
    checkout scm

    docker.withRegistry('https://hub.docker.com', 'dockerHub') {

        def customImage = docker.build("kiran7672/myjavaimage")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
