# tunichan-classic
##installation
>build the image
docker build -t tunichan .
>docker config
docker config create nginx nginx.conf
>deploy
docker-compose up -d
>if not using traefik and don't wanna mess with code
docker network create -d overlay webgateway
