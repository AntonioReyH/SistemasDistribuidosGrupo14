# Variables
DOCKER_COMPOSE = docker compose

# Comandos para iniciar los servicios individuales
docker-gobierno:
	$(DOCKER_COMPOSE) up --build gobierno

docker-cazarrecompenzas:
	$(DOCKER_COMPOSE) up --build cazarrecompenzas

docker-marina:
	$(DOCKER_COMPOSE) up --build marina

docker-submundo:
	$(DOCKER_COMPOSE) up --build submundo

# Comando para detener todos los servicios
docker-stop:
	$(DOCKER_COMPOSE) down

# Comando para reconstruir todas las imágenes y reiniciar los servicios
docker-restart:
	$(DOCKER_COMPOSE) down
	$(DOCKER_COMPOSE) up --build