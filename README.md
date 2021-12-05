# INSTALL


- First install docker and docker-compose on linux machine

(Install Docker)[https://docs.docker.com/engine/install/#server]
(Install Docker Compose)[https://docs.docker.com/compose/install/]

- To clone this repo, you use the command `git clone --recursive https://github.com/smc181002/cms-docker`

- Now go to the cms-api dir inside the repo and create .env file with the mongo URI 
which is given in the PDF submitted along with the project
```
DB_URL="mongodb+srv://admin:<password>@itlab0.homod.mongodb.net/slms"
```

- Now press the below command and the server will be running on port 3000 (open the link http://localhost:3000 ONLY)
```sh
docker-compose build
docker-compose up
```
