# A simple image running Php 5 and Mysql to run Legacy projects

## How to run: 
 
    docker run -d -p $PORT:$DOCKER_PORT  -v "$PWD":/var/www/html vtrgomes/docker-php5-mysql php -S 0.0.0.0:$DOCKER_PORT /var/www/html