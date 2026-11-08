# Dreams Estética — archivos PWA

Archivos:
- `manifest.json`
- `icons/icon-192.png`
- `icons/icon-512.png`

## Publicación
Subir la estructura completa a la rama `main` del repositorio `dreams-estetica-pwa` y activar GitHub Pages desde `Settings > Pages > Deploy from a branch > main > /(root)`.

URL esperada del manifiesto:
`https://lotusb99.github.io/dreams-estetica-pwa/manifest.json`

**Importante:** este paquete prepara el manifiesto y los iconos, pero no garantiza por sí solo que Chrome permita instalar el sitio. Como Blogger y GitHub Pages son dominios distintos, hay que comprobar que Chrome acepte el manifiesto externo y que el `start_url`/`scope` correspondan al dominio del blog. No incluye Service Worker ni Firebase Messaging.
