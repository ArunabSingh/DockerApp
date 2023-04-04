#Creating a basic JS/NodeJS App to revise Docker Skills

Used the following ways to build images and use them with the web app.
- Command Line
    - Built the images for mongo and mongo-express usin the command line.
- docker-compose.yaml file
    - Built and ran the images for Mongo and mongo-express using the docker-compose.yaml file
    - To build the images, use the following command
    `docker-compose -f docker-compose.yaml up -d`
- Dockerfile
    - Built the image for the web application using Dockerfile.
    - To run the image, use the following command
    `docker build -t myapp:1.0`