# README #

Docker LEMP Container, including a Magento CE 1.9.3.2 installation

### What is this repository for? ###

* This repository contains a Docker LEMP environment, with Nginx, PHP FPM and MySQL containers, along a PHPMyAdmin container. It uses local mounted volumes, helping the development process.

### How do I get set up? ###

* To use this environment, you must have Docker Compose installed. To get Docker Composer, visit https://docs.docker.com/compose/
* Clone this repository, using the last commit or a specific one
* Using the terminal, navigate to the folder 'docker/' and type 'docker-compose up -d'. Docker Compose will download the images and prepare the environment
* Dont forget to add the desired URL address your hosts file. For example, for Magento 1.9.3.2, we use m1.docker.dev
* The folder 'htdocs/' contains the online files and you can use the folder 'project/' to your development. Dont forget to deploy files from 'project/' to 'htdocs'
* You can also tune Nginx and PHP FPM via config files within theirs folders at 'docker/'
* If you need, you can reach PHPMyAdmin panel from localhost:8084

### Contribution guidelines ###

* If you want to contribute to this repository, just submit your Pull Request

### Who do I talk to? ###

* Andre Gugliotti - andre@gugliotti.com.br