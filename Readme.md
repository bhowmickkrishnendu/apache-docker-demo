# Apache Docker Demo

This is a simple demo project that shows how to run an Apache web server inside a Docker container. 

## Prerequisites

- [Docker](https://www.docker.com/get-started) must be installed on your machine.

## Usage

1. Clone this repository:

git clone https://github.com/bhowmickkrishnendu/apache-docker-demo.git


2. Navigate to the cloned directory:

cd apache-docker-demo


3. Build the Docker image:

docker build -t apache-demo .


4. Run the Docker container:

docker run -d -p 8080:80 apache-demo


5. Open your browser and go to `http://localhost:8080`. You should see the Apache default page.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
