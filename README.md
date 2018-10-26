Docker Compose Example
===

Taken from tutorial: https://scotch.io/tutorials/create-a-mean-app-with-angular-2-and-docker-compose

# Angular front end (client)
1. Build the docker container: `docker build -t angular-client:dev .`
1. Run the docker container: `docker run -it --name angular-client -p 4200:4200 angular-client:dev`
1. View the front end on your host computer at `http://localhost:4200`

