# Ejecutar
1. Clonar proyecto
2. Clonar el archivo ```.env.template``` y renombrarlo a ```.env```
3. Llenar las variables de entorno

4. Crear la red docker
```
docker network create network_name
```

5. Crear el contenedor
```
docker-compose up -d
```