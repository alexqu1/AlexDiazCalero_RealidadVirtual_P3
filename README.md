# Estación espacial: experiencia 360° con A-Frame

## 1. Descripción del proyecto

Este proyecto consiste en la creación de dos escenas de realidad virtual utilizando A-Frame y tecnologías web. Las dos escenas están ambientadas en una estación espacial futurista y permiten explorar el entorno mediante una vista de 360 grados.

La primera escena utiliza una imagen panorámica como fondo, mientras que la segunda utiliza un vídeo 360° para ofrecer una experiencia más dinámica e inmersiva.

## 2. Tecnologías utilizadas

- **HTML5:** estructura de las páginas web.
- **A-Frame:** framework para crear experiencias de realidad virtual en el navegador.
- **Imagen panorámica 360°:** utilizada como entorno de la primera escena.
- **Vídeo 360°:** utilizado como entorno de la segunda escena.

## 3. Estructura del proyecto


estacion-espacial/
├── sky.html
├── videosphere.html
├── README.md
├── img/
│   ├── img360.jpg
│   └── TexturaCubo.png
└── video/
    └── video360.mp4


## 4. Escena con imagen 360° (`sky.html`)

La primera escena utiliza el componente `<a-sky>` de A-Frame para mostrar una imagen panorámica que envuelve al usuario y crea la sensación de encontrarse dentro de una estación espacial.

Además, incluye un cubo con una textura futurista aplicada mediante el atributo `src`. La cámara permite observar el entorno y el cursor facilita la interacción con los elementos de la escena.

## 5. Escena con vídeo 360° (`videosphere.html`)

La segunda escena utiliza el componente `<a-videosphere>` para proyectar un vídeo panorámico sobre una esfera que rodea la cámara.

El vídeo se reproduce en bucle y está configurado para permanecer silenciado, facilitando su reproducción automática en el navegador. También se incluye un cubo con una textura futurista para mantener elementos comunes entre ambas escenas.

## 6. Cómo ejecutar el proyecto

1. Descargar o copiar todos los archivos del proyecto, manteniendo la estructura de carpetas.
2. Comprobar que las imágenes y el vídeo tienen los nombres y extensiones indicados en el código HTML.
3. Abrir `sky.html` en un navegador compatible para visualizar la escena con imagen 360°.
4. Abrir `videosphere.html` para visualizar la escena con vídeo 360°.
5. Mover la vista con el ratón para explorar el entorno. Si se dispone de un dispositivo compatible, también se puede probar el modo de realidad virtual.

Si el vídeo o las imágenes no se cargan correctamente al abrir los archivos directamente, se recomienda ejecutar el proyecto mediante un servidor web local.

## 7. Objetivos

- Familiarizarse con la creación de escenas de realidad virtual mediante A-Frame.
- Diferenciar el uso de `<a-sky>` para imágenes panorámicas y `<a-videosphere>` para vídeos 360°.
- Integrar recursos multimedia externos en una escena web.
- Añadir objetos tridimensionales con texturas para enriquecer el entorno virtual.

## 8. Conclusión

La práctica permite comparar dos formas de crear entornos inmersivos mediante tecnologías web. La imagen panorámica proporciona un escenario estático, mientras que el vídeo 360° añade movimiento y una mayor sensación de inmersión.

El proyecto sirve como introducción al desarrollo de experiencias de realidad virtual accesibles desde un navegador mediante A-Frame.
