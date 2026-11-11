# TA-IND-01 — Informe académico individual: análisis crítico de un sistema distribuido real

Aplicaciones Distribuidas (ISR-701) · Universidad Técnica Estatal de Quevedo · SPA 2026–2027

**Estudiante:** Castro Coello Mario Sebastián

## Video

Enlace al video (3–5 min): _pendiente_

## Contenido del repositorio

| Ruta | Descripción |
|---|---|
| `main.tex` | Archivo principal del informe |
| `referencias.bib` | Referencias (BibLaTeX, estilo IEEE) |
| `figuras/` | Diagramas y foto del esquema a mano |
| `capturas/ejecucion/` | Capturas de ejecución del sistema |
| `capturas/lectura/` | Capturas de los artículos citados, subrayados o anotados |
| `experimento/` | Comandos y resultados del experimento |
| `BITACORA.md` | Bitácora de trabajo por sesión |
| `main.pdf` | Informe compilado |

## Compilación del informe

- **Compilador:** `pdflatex`
- **Bibliografía:** `biber` (paquete `biblatex` con estilo `ieee`)
- **Archivo principal:** `main.tex`
- **Distribución usada:** MiKTeX 26.5 en Windows

Orden de comandos, ejecutados desde la raíz del repositorio:

```bash
pdflatex main.tex
biber main
pdflatex main.tex
pdflatex main.tex
```

El resultado es `main.pdf`.

### Dependencias

Paquetes de LaTeX: `fontenc`, `inputenc`, `babel` (idioma `spanish`), `lmodern`, `microtype`,
`geometry`, `graphicx`, `booktabs`, `tabularx`, `float`, `xcolor`, `listings`, `csquotes`,
`biblatex` con `biblatex-ieee`, y `hyperref`. Además se necesita el programa `biber`.
MiKTeX instala automáticamente los paquetes que falten; en TeX Live vienen incluidos en el
esquema completo (`scheme-full`).
