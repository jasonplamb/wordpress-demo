# Pilw.io Docker Conference - Demo #1

The following repository aims to provide a documented version of demo #1 aimed at providing a working environment, using Docker, aimed at pre-dominantly at **developers**. It is currently not intended for deployment.. that can come later :)

## Usage

 - Clone this repository using Git to a folder of your choice

    git clone https://github.com/jasonplamb/wordpress-demo.git wordpress-demo

 - Change into the folder created during the clone

    cd wordpress-demo

 - Bring up the containers

    docker-compose up

- Eventually the logs should stop flying past in which case you can view wordpress (http://localhost) and phpmyadmin (http://localhost:8080)

## Additional Notes

Check out the docker-compose.yml. I've added some additional features with comments based on the presentation.
