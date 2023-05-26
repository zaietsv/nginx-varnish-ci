# nginx-varnish-ci
Docker configuration of a container Nginx interacting with Varnish cache

## server URLs

http://www.nginx-varnish.ci/

http://nginx-varnish.ci/

## Sample pages

http://www.nginx-varnish.ci/index.html

http://www.nginx-varnish.ci/page.html

http://www.nginx-varnish.ci/errors/404.html

http://www.nginx-varnish.ci/errors/50x.html

## Managing a Docker container
### Running a container
    docker-compose up --build
### List all running containers
    docker ps
### Entering a container
    docker exec -it src_www-data_1 bash
### Shutting down a container
    docker-compose down --remove-orphans
