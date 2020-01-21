Dockerfile:

    - This Dockerfile builds a imagem that contains php extensions for mysql and sqlserver databases

docker-compose

    - Here we have an stack with wordpress + phpmyadmin + mariadb

Instructions:

    - 1 docker build -t wp_custom:v1 .
    - 2 export DB_PASSWORD=YOU_STRONG_PASSWORD_PLEASE_STRONG
    - 3 docker stack deploy wordpres.yml wp (if you are deploy in a SWARM cluster)
        - 3.1 docker-compose up (if you are running on your computer)


