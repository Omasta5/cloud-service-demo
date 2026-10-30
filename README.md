# Cloud Service Demo

This project demonstrates a sample cloud-based service, representing how an application like this could be hosted in the cloud.

- README.md
- index.html

Version control helps a cloud project by tracking changes, enabling collaboration, and making it easy to roll back to stable versions when needed.

Docker is a platform that allows users to place an application inside of a isolated unit called a container, as a way to make sure that their application can properly run on devices.
A Docker image is created using a Dockerfile to act as a base or blueprint for a container.
A Docker container is used to help run applications through multiple devices.
To build and run an application using Docker, first make sure the system you are working with has Docker installed, then make a Dockerfile. After making it, build the Docker image for the application through using the command 'docker build -t cloud-service-demo:1.0 .', then run a conatiner of the image using the command 'docker run -d --name cloud-demo-container -p 8080:80 cloud-service-demo:1.0 ', and finally check to make sure application is properly running using the appropriate localhost in a browser. 