# Basic Docker Compose
This yml file shows an example of how to use docker-compose to launch a wordpress site using multiple containers. In this case it is launching one container using the wordpress image and other for the mysql database.

## Step 1: Clone the Repo
Clone the repo to a local directory. Once the repo is cloned locally, move to folder containing the docker-compose.yml file


## Step 2: Launch Containers
 Run following command:

`docker-compose up -d`

> -d flag indicates the containers would run in detached mode.

This would pull the required images from docker hub and fire up the required containers. You can view the list of running containers by running following command:

`docker container ls`

**Note:**

Please ensure following are installed before you run docker compose:

- [x] [Docker desktop](https://www.docker.com/products/docker-desktop)
- [x] [Docker compose](https://docs.docker.com/compose/install/)


## Step 3: Running the WordPress site
 Open up your favorite browser and navigate to (http://localhost:5001). You should now see the WordPress site!!


## Step 4: Stopping the containers
 Run following commands if you would like to stop the containers:
 
 `docker-compose down`