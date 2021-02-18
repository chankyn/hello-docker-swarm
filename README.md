# hello-docker-swarm
Demo de docker swarm con docker-compose; se utiliza una imagen del repositorio privado de gitlab.

Pasos para ejecutar:
- Iniciar docker swarm -> docker swarm init
- Lanzar el stack -> docker stack deploy/up -c docker-compose.yml --with-registry-auth brunch
