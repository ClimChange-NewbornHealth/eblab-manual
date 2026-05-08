# Lab manual (Quarto)

Manual ejecutivo del laboratorio **ClimChange-NewbornHealth**: exposición ambiental y salud perinatal. El sitio se genera con [Quarto](https://quarto.org/) como libro HTML.

## Desarrollo local

```bash
quarto preview
# o
quarto render
```

Salida: carpeta `_site/` (ignorada en git).

## Publicación (GitHub Pages)

1. El repositorio remoto debe llamarse **`lab-manual`** bajo la organización [ClimChange-NewbornHealth](https://github.com/ClimChange-NewbornHealth) para que la URL estándar sea  
   **https://climchange-newbornhealth.github.io/lab-manual/**
2. Con cada push a `main`, el workflow [`.github/workflows/publish.yml`](.github/workflows/publish.yml) renderiza y publica en la rama `gh-pages`.
3. En el repositorio: **Settings → Pages → Branch `gh-pages` / folder root**.

Lineamientos de repos y datos: [Lineamientos_colaboradores](https://github.com/ClimChange-NewbornHealth/Lineamientos_colaboradores).

## Licencia

MIT — ver [`LICENSE`](LICENSE).
