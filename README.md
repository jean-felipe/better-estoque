

Main commands for docker:

to start:

 docker run -v "$PWD":/usr/src/app -p 3000:3000 --network=better-network better-estoque

rake commands:
docker run -v "$PWD":/usr/src/app --network=better-network better-estoque rake db:create
