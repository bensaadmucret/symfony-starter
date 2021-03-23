# symfony-starter
symfony starter project

-- docker-compose build
-- docker-compose up-d
-- docker exec www_docker_symfony composer create-project symfony/website-skeleton project
-- sudo chown -R $USER ./
Une fois l’installation terminée, en vous rendant à l’adresse http://127.0.0.1:8741/, vous devriez voir la page standard d’un nouveau projet Symfony ! 
-------------------------------------------------------------------------------------------------
Pour entrer dans le shell du conteneur “www”.
docker exec -it www_docker_symfony bash