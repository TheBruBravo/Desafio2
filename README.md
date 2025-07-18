# Documentación para replicar el pipeline de Jenkins

## Requisitos previos

1. Crear una network que utilizaran la suite de monitoreo y Jenkins
   ```sh
   docker network create shared-net
   ```
2. Jenkins con Docker y Docker-Compose instalados, plugins recomendados por defecto al instalar jenkins.
3. Tener una cuenta en Docker Hub y credenciales configuradas en Jenkins (el codigo del pipeline busca el id dockerhub_credentials, pero puede modificarse).
