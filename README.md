# Ejecutar
1. Clonar el repositorio
2. Clonar el archivo ```.env.template``` y renombrarlo a ```.env```
3. Llenar las variables de entorno

4. Crear la red docker
```
docker network create nginx-proxy
```

5. Crear el contenedor
```
docker-compose up -d
```
