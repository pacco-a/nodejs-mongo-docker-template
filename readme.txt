# Démarrer les container
docker-compose up
ou 
docker-compose up -d // en mode background
ou
docker-compose up --build // si l'image docker a changé

# Entrer dans le shell
docker-compose exec node /bin/sh