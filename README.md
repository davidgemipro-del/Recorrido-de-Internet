# Ruta de un mensaje

Simulador educativo del recorrido de una solicitud desde un navegador hasta una aplicación en la nube. Todo el funcionamiento está contenido en `index.html`; no usa dependencias, servidor, base de datos ni proceso de compilación.

## Probarlo localmente

Abre `index.html` con cualquier navegador moderno. También puedes servir la carpeta con un servidor HTTP local si el navegador restringe alguna función al abrir archivos directamente.

## Publicarlo en GitHub

1. Crea un repositorio vacío en GitHub.
2. Sube el contenido de esta carpeta, procurando que `index.html` quede en la raíz del repositorio.
3. Si deseas usar GitHub Pages, abre **Settings → Pages**, elige **Deploy from a branch** y selecciona la rama principal y la carpeta raíz.

## Publicarlo en Netlify

### Desde GitHub

1. En Netlify, selecciona **Add new site → Import an existing project**.
2. Conecta el repositorio de GitHub.
3. Deja vacío **Build command**.
4. Usa `.` como **Publish directory**.
5. Publica el sitio.

### Arrastrando la carpeta

También puedes abrir **Netlify Drop** y arrastrar esta carpeta completa. Netlify detectará `index.html` automáticamente.

## Archivos

- `index.html`: estructura, estilos, animaciones y lógica de la simulación.
- `netlify.toml`: configuración de publicación y encabezados básicos de seguridad.

## Uso en clase

Escribe un mensaje, selecciona un escenario y presiona **Enviar mensaje**. La simulación puede pausarse o avanzar paso a paso. Cada etapa muestra el protocolo principal que interviene. Las direcciones IP y la infraestructura mostradas son ejemplos educativos; no describen una red institucional real.
