Docker Compose Example
===

# Angular front end (client)
1. Build the docker container: `docker build -t angular-client:dev .`
1. Run the docker container: `docker run -it --name angular-client -p 4200:4200 angular-client:dev`

