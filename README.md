# Tensorflow docker setup
Test repo to setup tensorflow docker container

* Build the image defined by the Dockerfile
  `docker build -t tensorflow_docker_setup .`

* Run an interactive bash sell within the container
  `docker run --rm -it tensorflow_docker_setup bash`

* Run the tensorflow script
  `python cnn_mnist.py`
