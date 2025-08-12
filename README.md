# n8n-revealjs Nginx Docker

Este proyecto sirve un archivo `index.html` usando Nginx en un contenedor Docker.

## Archivos principales
- `index.html`: Tu archivo HTML principal.
- `Dockerfile`: Define la imagen Docker basada en Nginx.
- `nginx.conf`: Configuración personalizada de Nginx.

## Uso rápido

### 1. Construir la imagen

```sh
docker build -t mi-nginx .
```

### 2. Ejecutar el contenedor

```sh
docker run -p 8080:80 mi-nginx
```

Abre tu navegador en [http://localhost:8080](http://localhost:8080) para ver el sitio.

## Personalización
- Modifica `index.html` para cambiar el contenido.
- Ajusta `nginx.conf` si necesitas rutas o configuraciones adicionales.

---

Hecho con ❤️ para servir contenido estático de forma sencilla.
