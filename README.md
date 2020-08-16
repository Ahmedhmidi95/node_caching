# Node caching using Redis

## Requirements:
- Node JS
- NPM
- Postman/Web Browser
- Code Editor (VsCode)

## Install Required modules
npm install

## Install Redis
- wget http://download.redis.io/redis-stable.tar.gz
- tar xvzf redis-stable.tar.gz
- cd redis-stable
- make
- sudo make install

## Check Redis installation
### run Redis Server
- redis-server
- redis-cli ping
=> You should get PONG as a response

## Run the node caching app:
- npm start

## Check response time with more than one call to the recipes API and see the difference !
- GET/ http://localhost:3000/recipe/chips