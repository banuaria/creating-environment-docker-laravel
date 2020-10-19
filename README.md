## SET UP ENVIROMENT

Requirements:

-Docker <br>
-Docker Compose

before running "docker-compose up -d" for the first time, u need to run the following commands:

'''bash
docker-compose run --rm -v $HOME/.cache/composer:/tmp -e COMPOSER_HOME=/ php composer install
docker-compose run --rm node npm install
'''

now u can run:

'''bash
docker-compose up -d
'''
