regarder les conteneurs actifs : `sudo docker ps`

supprimer les conteneurs : `sudo docker rm container_name`

construire son conteneur : `sudo docker build -t alpine-sshd ./src`

Créer un volume : `sudo docker volume create mock-db`

Monter un volume sur un conteneur : `sudo docker run -d -p 127.0.0.1:22:22 --mount type=volume,src=mock-db,target=/home/eve/Documents/dockertest alpine-sshd:latest`

se connecter : `ssh user@127.0.0.1`
