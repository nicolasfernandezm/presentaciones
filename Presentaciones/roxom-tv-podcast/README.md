# Roxom TV Podcast

Presentacion HTML estatica para propuesta Gloaming.

## Como abrir localmente

1. Abri `index.html` desde la carpeta `roxom-tv-podcast`.
2. Si preferis servidor local, desde esa carpeta ejecuta:

```bash
python -m http.server 8000
```

## Despliegue en Vercel

1. Subi esta carpeta a GitHub.
2. Importala en Vercel como proyecto nuevo.
3. Dejalo como sitio estatico, sin `build command`.
4. Como `index.html` esta en la raiz del proyecto, Vercel lo sirve sin configuracion extra.

## Notas

- No es necesario `vercel.json` para este caso.
- Las rutas de assets son relativas y apuntan correctamente a `assets/`.
