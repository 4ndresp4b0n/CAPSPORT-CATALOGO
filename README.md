# Cap Sport — Catálogo 2026

Catálogo digital de productos de Cap Sport, pensado para compartir por WhatsApp.

- `index.html` — catálogo web interactivo (buscador, filtros, categorías, enlaces directos a WhatsApp).
- `catalogo.pdf` — versión en PDF del mismo catálogo, para enviar como archivo.
- `nike.html` — catálogo aparte, solo modelos Nike (hombre y mujer), sin marca Cap Sport ni WhatsApp/carrito: se sirve como `/nike.html` en el mismo dominio.

Datos de producto (marca, referencia, precio, tallas) tomados del catálogo real en [capsport.com.co](https://capsport.com.co). Los datos de `nike.html` vienen de listas de precios mayoristas Nike.

## Configuración

El número de WhatsApp está en `index.html`, dentro de `<script>`, en `CONFIG.WHATSAPP_NUMBER`. Edítalo ahí si cambia.
