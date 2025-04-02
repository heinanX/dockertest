Docker Test for Building an Image and Running a Container:

In this repository, a Docker image will be built for a simple cowsay application and run as a container. The steps are as follows:

    Build the Docker image
    Use the docker build command to create a Docker image:

docker build -t cowsay .

    -t cowsay gives the image the name "cowsay".

    The . refers to the current directory where the Dockerfile is located.

Run a Docker container from the image
Once the image is built, a container can be created and started using the docker run command:

    docker run --name mycowsay cowsay

        --name mycowsay assigns the container the name "mycowsay".

        cowsay refers to the image name that was built earlier.

This will start the container, and the output from the cowsay application will be displayed.
