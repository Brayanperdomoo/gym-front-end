# GymFlow Frontend

Frontend moderno para sistema de gimnasio.

## Módulos

- Miembros
- Entrenadores
- Sesiones de entrenamiento

## Tecnologías

- HTML5
- CSS3
- JavaScript
- Bootstrap 5
- Bootstrap Icons

## Validaciones

- Nombres y apellidos solo permiten letras y espacios.
- Documento y celular solo permiten números.
- Documento y celular deben tener entre 10 y 12 dígitos.
- Correos con formato válido.
- Fechas de sesión no pueden estar en el pasado.
- Duración de sesión entre 15 y 240 minutos.
- Selects obligatorios para miembro y entrenador.

## Uso local

Abrir `index.html` con Live Server y tener el backend corriendo en:

```txt
http://localhost:8080/api
```

## Deploy

Antes de desplegar, cambiar en `app.js`:

```js
const PRODUCTION_API_URL = "https://gym-back-end.onrender.com/api";
```

por la URL real del backend en Render.
