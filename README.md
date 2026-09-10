# Ondas Digitales — Portal Web Multimedia (VIDEO1)

Proyecto del Desafío Práctico: Programación Web I. Sitio construido
únicamente con HTML5 semántico y CSS fluido tradicional (sin Flexbox,
CSS Grid, Media Queries ni JavaScript).

## Estructura
```
proyecto-video1/
├── index.html
├── guia-explicativa.html
├── README.md
├── css/
│   └── styles.css
└── img/
    ├── ia-cotidiana.svg
    ├── microfono-podcast.svg
    └── web-accesible.svg
```

## Antes de entregar
1. Reemplaza el contenido de la sección `#resumen` en `index.html` por el
   resumen real que genere NotebookLM a partir del episodio que elegiste.
2. Verifica que el ID del video (`IwaF7-COu1c`) corresponda al episodio
   indicado por el docente.
3. Valida `index.html` y `css/styles.css` en el validador oficial de la
   W3C: https://validator.w3.org/ y https://jigsaw.w3.org/css-validator/

## Publicar en GitHub (repositorio + GitHub Pages)
```bash
cd proyecto-video1
git init
git add .
git commit -m "Estructura base: HTML5 semántico y CSS fluido"
git branch -M main
git remote add origin https://github.com/<tu-usuario>/<tu-repo>.git
git push -u origin main
```
Luego, en GitHub: **Settings → Pages → Branch: main → carpeta /(root)**.
El sitio quedará publicado en:
`https://<tu-usuario>.github.io/<tu-repo>/`

Recuerda hacer varios commits pequeños y descriptivos a medida que avanzas
(estructura, estilos, contenido, imágenes) para evidenciar un flujo de
desarrollo incremental.
