# Intstructions

  docker ps -a
  docker system prune -a

  #### Build directly for linux
  docker buildx build --platform linux/amd64 -t {project-name} .
