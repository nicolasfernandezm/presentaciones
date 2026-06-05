# Presentaciones HTML

Repositorio con varias presentaciones HTML estaticas para propuesta Gloaming.

## Estructura

- `belada-padel-presentacion/`
- `belada-padel-presentacion-vercel/`
- `copa-marea-v2/copa-marea-v2/`
- `pepsi-mango-beat/`
- `roxom-tv-podcast/`

Cada una es una pagina estatica independiente con su propio `index.html`, CSS, JS y assets relativos.

## Como abrir localmente

1. Entrar a la carpeta del demo que quieras revisar.
2. Abrir `index.html` directamente en el navegador, o levantar un servidor local desde esa carpeta.

Ejemplo:

```bash
python -m http.server 8000
```

## Como desplegar en Vercel

1. Subir este repositorio a GitHub.
2. Importar en Vercel como proyecto nuevo.
3. Elegir como `Root Directory` la carpeta del demo que quieras publicar.
4. Dejar el proyecto como sitio estatico, sin `build command`.

## Notas

- No existe un `index.html` en la raiz del repositorio.
- Por eso no hace falta un `vercel.json` global.
- La carpeta `belada-padel-presentacion-vercel/` ya esta preparada como variante para Vercel.
