# drupal-7-docker
Yoti Docker module for Drupal 7 including Yoti plugin.

## Setup

Clone this repos and run the following commands: 

`cd drupal-7-docker`

`docker-compose build` to rebuild the image.

`docker-compose up -d` to build the containers.

Browse the link below and follow the instructions

`http://localhost:8007`

## Database Configuration
Enter the following details for the database

User Name `drupal`

Password `drupal`

Database Name `drupal`

Host `yoti-drupal-7-db`

## Yoti plugin setup
Please follow the instructions [here](https://github.com/getyoti/yoti-drupal-7) to set Yoti up.

## Removing docker containers
Run the following commands to remove docker containers:

`docker-compose stop` and

`docker-compose rm`
