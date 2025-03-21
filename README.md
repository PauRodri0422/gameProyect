# GAME-PROYECT

¡Bienvenido a **GAME-PROYECT**! Este es un juego clásico de Breakout. El objetivo del juego es controlar una paleta con las flechas del teclado para rebotar una pelota y romper ladrillos. Este proyecto utiliza el elemento `<canvas>` de HTML5 y su API para renderizar gráficos y animaciones.


## Descripción

**GAME-PROYECT** es un juego interactivo donde los usuarios controlan una paleta para rebotar una pelota y romper ladrillos. El proyecto incluye:

- **Animaciones fluidas** usando `requestAnimationFrame`.
- **Detección de colisiones** entre la pelota, la paleta y los ladrillos.
- **Puntuación** que aumenta a medida que se rompen los ladrillos.
- **Reglas del juego** accesibles a través de un botón con un deslizador.


## Tecnologías Utilizadas

- **Frontend**: HTML5, CSS, JavaScript (ES6+)
- **Herramientas de desarrollo**: Webpack, Babel
- **Linters**: Webhint, Stylelint, ESLint
- **Backend**: Node.js, Express (para el servidor local)
- **Despliegue**: Azure App Service

## Instalación

Sigue estos pasos para configurar el proyecto localmente:

1. Clona el repositorio:
   ```bash
   git clone https://github.com/PauRodri0422/game-proyect.git
2. Instala las dependencias:
    ```bash
    npm install
3. Compila el proyecto:
    ```bash
    npm run build
4. Inicia el servidor de desarrollo:
    ```bash
    npm start
5. Abre tu navegador y visita:
    http://localhost:3000

## Uso
**Controles:**

- Usa las flechas ← y → para mover la paleta.

- Presiona el botón "Rules" para ver las reglas del juego.

**Objetivo:**

- Rompe todos los ladrillos para ganar.

- Evita que la pelota caiga por debajo de la paleta.

## Configuración de Linters
El proyecto incluye linters para asegurar la calidad del código:
- Webhint: Para archivos HTML.

- Stylelint: Para archivos CSS.

- ESLint: Para archivos JavaScript.

Los linters se ejecutan automáticamente en cada push o pull request gracias a GitHub Actions.

## Despliegue en Azure
El proyecto está desplegado en Azure App Service. Para acceder al juego, visita:
https://nombre-de-tu-app.azurewebsites.net

**Pasos para desplegar en Azure:**
1. Crea un recurso de App Service en Azure.

2. Conecta tu repositorio de GitHub al App Service.

3. Configura los secretos en GitHub:

    - AZURE_WEBAPP_NAME: Nombre de la aplicación en Azure.

    - AZURE_WEBAPP_PUBLISH_PROFILE: Perfil de publicación descargado desde Azure.

4. Realiza un push para desplegar automáticamente.

## Licencia
Este proyecto está bajo la licencia MIT. Para más detalles, consulta el archivo LICENSE.

¡Gracias por visitar GAME-PROYECT! 😊
