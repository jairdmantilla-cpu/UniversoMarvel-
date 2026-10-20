# Universo Marvel (versión superior)

Sitio web de Marvel hecho con HTML, CSS y JavaScript (sin librerías).
Combina el **diseño y contenido originales** (barra gris, fondo negro, tarjetas, cartas que giran, línea de tiempo,
videos de los juegos) con la **estructura ordenada y las funciones completas** (sesión por roles, tienda, carrito,
pago, suscripciones y panel de administración).

## Cómo abrirlo
1. Descomprime la carpeta.
2. Abre `index.html` con **Chrome o Edge** (doble clic), o con la extensión *Live Server* de VS Code.

## Estructura
- `index.html` (login), `registro.html`, `recuperar.html`
- `inicio.html`, `comic.html`, `personajes.html`, `juegos.html`, `juego.html`, `cronologia.html`
- `tienda.html`, `carrito.html`, `perfil.html`, `admin.html`
- `css/estilos.css`: estilos de todo el sitio (dividido en secciones numeradas)
- `js/datos.js`: cómics, personajes, juegos, cronología y productos
- `js/comun.js`: funciones que usan todas las páginas (guardar datos, sesión, menú...)
- `img/` y `video/`: imágenes y videos

## Usuarios de prueba (administradores)
| Correo | Clave | Rol |
|---|---|---|
| Jarman@gmail.com | 12345 | admin |
| Rocha@gmail.com | 12345 | admin-content |
| Cruz@gmail.com | 12345 | admin-sales |

Los demás usuarios se crean desde `registro.html`.

## Recuperar contraseña
Funciona en modo simulado. Para enviar correos reales, escribe tus claves de EmailJS en `js/comun.js` (`emailjsConfig`).

## Nota
Los datos (usuarios, carrito, ventas) se guardan en el `localStorage` del navegador. Todavía no hay conexión a la base de datos MySQL.
