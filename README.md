1. Construir la imagen

- Clonar el repositorio localmente y posicionarse en el directorio que contiene el código clonado.
- Luego ejecutar el sigueinte comando.

    docker build -t docker_exam .


2. Correr el contenedor

- Ejecutar el siguiente comando para levantar el contendor.

    docker run -p 3000:3000 docker_exam


3. Levantar el servicio con docker compose

- Ejecutar el siguiente comando para levantar el contendor.

    docker compose up