# Docker-compose

The gole of this project to create multi docker container create Two application  node & mongo in seprate container and and this two aplliction are in another container
for more understanding check the image.


Step 1 : Install node and mongo in youre mashine


Step 2 : Create .dockerignore file to ignore node_modules folder


Step 3 : create a node application


Step 4 : build a image of node application (docker build -t nodes .)


Step 5 : Start the docker node application/node image (docker run nodes)


Step 6 : Create docker compose file to create multiple container and connectio between them (https://docs.docker.com/compose/)


Step 7 : docker-compose up --build (use --build for up and ruuning container  & up is only for up the container ) use this for run your entire app


Step 8 : Application is Ready (Check the port no.8000 its running)



![Screenshot (157)](https://user-images.githubusercontent.com/85119097/193325149-b79e0a88-9672-47af-8b36-36d23da9fd59.png)
