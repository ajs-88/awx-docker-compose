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

Note: Give it few mins ;)

Step 5:
Login and start using awx.
http://localhost:8052

admin / password

Additional Notes:
1. Use SVN or Git to store your ansible config files
2. Make backups of ansible database as needed.
3. Create new admin users and rename defaults.
