# awx-docker-compose

To make your awx production ready, i would highly encourage you to do it like the following,

Step 1:
Download the docker-compose.yml file

Step 2:
Use postgresql server on your server not as a docker image.

Step 3:
create database and grant privilages as mentioned in the docker-compose.yml file or create your own and relpace them in the docker-compose.yml file.

Step 4:
docker-compose up -d

Step 5:
Login and start using awx.
