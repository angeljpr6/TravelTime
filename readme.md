# Travel Time Applet

## Descripción
El applet **Travel Time** calcula y muestra el tiempo aproximado de viaje entre dos ubicaciones ingresadas por el usuario. Utiliza múltiples bibliotecas y servicios para obtener la información necesaria y presentarla de manera comprensible.

## Características
- Ingreso de dos ubicaciones.
- Cálculo del tiempo aproximado de viaje entre las ubicaciones ingresadas.
- Visualización de resultados con imágenes representativas.

## Autor
- **angeljpr6**

## Instalación
Para instalar y ejecutar este proyecto, sigue los pasos a continuación:

1. Clona el repositorio en tu máquina local:
    ```sh
    git clone https://github.com/usuario/proyecto.git
    ```

2. Navega al directorio del proyecto:
    ```sh
    cd proyecto
    ```

3. Asegúrate de tener Starlark instalado. Puedes instalarlo siguiendo las instrucciones en [Starlark's GitHub page](https://github.com/bazelbuild/starlark).

## Uso
A continuación se muestra un ejemplo de cómo utilizar el applet de Travel Time:

1. Abre tu terminal y navega al directorio del proyecto.
2. Ejecuta el script principal:
    ```sh
    starlark travel_time.star
    ```

3. Ingresa las ubicaciones cuando se te solicite y el programa calculará y mostrará el tiempo de viaje aproximado.

## Estructura del Proyecto
El proyecto está organizado de la siguiente manera:
- `travel_time.star`: Script principal que contiene la lógica del applet.
- `render.star`: Biblioteca para renderizar las imágenes y el texto.
- `schema.star`: Define los esquemas de datos utilizados.
- `encoding/base64.star`: Biblioteca para decodificar imágenes en base64.
- `time.star`: Biblioteca para gestionar operaciones relacionadas con el tiempo.
- `http.star`: Biblioteca para realizar solicitudes HTTP.
- `encoding/json.star`: Biblioteca para manejar JSON.

## Contribuir
Si deseas contribuir a este proyecto, por favor sigue los pasos a continuación:

1. Haz un fork del repositorio.
2. Crea una nueva rama (`git checkout -b feature-nueva-funcionalidad`).
3. Realiza los cambios necesarios y haz commit (`git commit -am 'Agrega nueva funcionalidad'`).
4. Sube los cambios a tu fork (`git push origin feature-nueva-funcionalidad`).
5. Abre un Pull Request en este repositorio.

## Licencia
Este proyecto está bajo la licencia [MIT](LICENSE).

## Contacto
Si tienes alguna pregunta, no dudes en contactar al autor:
- GitHub: [angeljpr6](https://github.com/angeljpr6)
