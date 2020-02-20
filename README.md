						Application Deployment with Docker

Requirements:
        --> docker-compose

Setup: Run the following command to up our containers in root directory

# docker-compose up --build

Notes:
* We have separate Dockerfiles for each of services which enables to setup our application in a container.

Testing: Open another terminal and execute below command,

# ab -n 20 -c 10 http://localhost:8080/hotels

Now check cosole output in application running terminal.
