# SentinelOps Platform Public Landing

Web pública estática para presentar SentinelOps Platform sin exponer portal, API, credenciales, documentación interna ni endpoints operativos.

## Contenido

- `index.html`
- `styles.css`
- `_headers`
- `_redirects`

## Prueba local

```bash
cd web-public
python -m http.server 8080
```

Abrir:

```text
http://localhost:8080
```

## Cloudflare Pages

- Framework preset: `None`
- Build command: vacío
- Build output directory: `web-public`

Si todavía no quieres publicar, detente antes de hacer clic en `Save and Deploy` o `Deploy site`. Cloudflare Pages crea una publicación cuando ejecutas ese paso.

Después del deploy puedes agregar un Custom Domain desde Cloudflare Pages.

## Importante

Publicar solo esta landing comercial.

No publicar todavía:

- `/portal`
- `/api/docs`
- `/openapi.json`
- `/admin`
- `/demo interno`

Antes de publicar entornos interactivos, completar HTTPS, autenticación fuerte, hardening, backups y separación entre demo pública y entorno real.
