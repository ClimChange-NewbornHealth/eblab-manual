# Manual de trabajo · EB-Lab 📘

[![Render and Publish](https://github.com/ClimChange-NewbornHealth/eblab-manual/actions/workflows/publish.yml/badge.svg)](https://github.com/ClimChange-NewbornHealth/eblab-manual/actions/workflows/publish.yml)
[![GitHub Repo stars](https://img.shields.io/github/stars/ClimChange-NewbornHealth/eblab-manual?style=flat-square&logo=github)](https://github.com/ClimChange-NewbornHealth/eblab-manual)
[![GitHub forks](https://img.shields.io/github/forks/ClimChange-NewbornHealth/eblab-manual?style=flat-square&logo=github)](https://github.com/ClimChange-NewbornHealth/eblab-manual)
[![GitHub watchers](https://img.shields.io/github/watchers/ClimChange-NewbornHealth/eblab-manual?style=flat-square&logo=github)](https://github.com/ClimChange-NewbornHealth/eblab-manual)
[![Último commit](https://img.shields.io/github/last-commit/ClimChange-NewbornHealth/eblab-manual?style=flat-square&logo=github)](https://github.com/ClimChange-NewbornHealth/eblab-manual/commits/main/)
[![Actividad de commits](https://img.shields.io/github/commit-activity/t/ClimChange-NewbornHealth/eblab-manual?style=flat-square&logo=github)](https://github.com/ClimChange-NewbornHealth/eblab-manual/commits/main/)
[![Colaboradores](https://img.shields.io/github/contributors/ClimChange-NewbornHealth/eblab-manual?style=flat-square&logo=github)](https://github.com/ClimChange-NewbornHealth/eblab-manual/graphs/contributors)
[![Licencia](https://img.shields.io/github/license/ClimChange-NewbornHealth/eblab-manual?style=flat-square)](https://github.com/ClimChange-NewbornHealth/eblab-manual/blob/main/LICENSE)
[![Construido con Quarto](https://img.shields.io/badge/Quarto-75AADB?style=flat-square&logo=quarto&logoColor=white)](https://quarto.org/)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.20087987.svg)](https://doi.org/10.5281/zenodo.20087987)

Sitio libro HTML del **EB-Lab** sobre prácticas reproducibles del laboratorio (**exposición ambiental y salud perinatal**), alineado a los lineamientos de la organización [ClimChange-NewbornHealth](https://github.com/ClimChange-NewbornHealth).

## Autorías / contacto

:mailbox_with_mail: **Estela Blanco** ([estela.blanco@uc.cl](mailto:estela.blanco@uc.cl)) · [ORCID](https://orcid.org/0000-0002-6232-9210) · Investigadora principal (EB-Lab).

:mailbox_with_mail: **José Daniel Conejeros** ([jdconejeros@uc.cl](mailto:jdconejeros@uc.cl)) · [ORCID](https://orcid.org/0000-0003-3402-4361) · Colaborador de investigación · gestión de repositorios (*Research collaborator – Repository Manager*).

## Sitio publicado

- **Español:** [climchange-newbornhealth.github.io/eblab-manual/](https://climchange-newbornhealth.github.io/eblab-manual/)
- **Inglés:** […/eblab-manual/en/](https://climchange-newbornhealth.github.io/eblab-manual/en/) (traducción completa paralela).

## Render local

```bash
quarto preview
quarto render
cd english && quarto render && cd ..
```

La salida combinada va a `_site/` (español en raíz, inglés en `en/`). Esa carpeta se ignora en git; [**GitHub Actions**](https://github.com/ClimChange-NewbornHealth/eblab-manual/actions) publica en la rama `gh-pages` (Settings → Pages → `gh-pages` / `(root)`).

## Contenido del repositorio (resumen)

| Elemento | Descripción |
| --- | --- |
| `_quarto.yml` | Libro Quarto ES: título EB-Lab, autores/ORCID, nav **English**, pie con enlace **DOI** (Zenodo) |
| `custom.scss` | Estilos cercanos al sitio del laboratorio |
| `english/` | Misma versión en inglés → `_site/en/` |
| `assets/` | Logo y figuras tomadas del instructivo Lineamientos |
| `*.qmd` | Capítulos; incluye **Cómo contribuir** con capturas |

## Zenodo · DOI

Versión archivada: [registro en Zenodo](https://zenodo.org/records/20087988) · **DOI** [10.5281/zenodo.20087987](https://doi.org/10.5281/zenodo.20087987) (pie del libro en `_quarto.yml` y `english/_quarto.yml`).

## Recursos relacionados

- [**Lineamientos para colaboradores**](https://github.com/ClimChange-NewbornHealth/Lineamientos_colaboradores) (estructura de repos, datos fuera del remoto).
- Ejemplo de README con shields en la org: [**Pollution_Kriging**](https://github.com/ClimChange-NewbornHealth/Pollution_Kriging).

## Licencia

MIT — ver [`LICENSE`](LICENSE).
