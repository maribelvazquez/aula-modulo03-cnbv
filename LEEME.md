# Aula del Repaso · Módulo 3 · v2

Sitio de estudio del Área 3 del temario CNBV PLD/FT (2ª convocatoria, agosto 2026). Es un solo sitio: el portal está en la raíz y cada herramienta vive en su carpeta.

Cambios respecto a la v1: se activan ENR 2023 (3.3.3) y Guía Anticorrupción (3.3.4), ambas en su versión corregida tras la auditoría adversarial.

## Cómo publicarlo en Netlify
Actualiza el mismo sitio donde subiste la v1 (Deploys → arrastra la carpeta o el zip descomprimido) para que la liga de los alumnos no cambie. No necesita compilarse: `index.html` está en la raíz.

## Qué hay dentro
| Carpeta | Tema | Herramienta |
|---|---|---|
| (raíz) `index.html` | — | Portal «Aula del Repaso · Módulo 3» y Biblioteca de las 10 fuentes con su liga oficial |
| `3-1-1-auditoria/` | 3.1.1 | Lineamientos del Informe de Auditoría PLD/FT |
| `3-1-2-supervision/` | 3.1.2 | Reglamento de Supervisión de la CNBV |
| `3-2-1-gafi/` | 3.2.1 | Guía GAFI del EBR para el sector bancario |
| `3-2-2-basilea/` | 3.2.2 | Basilea, BCBS 275 |
| `3-3-1-metodologia/` | 3.3.1 | Metodología de evaluación de riesgos (Guía CNBV 2019 y DCG Cap. II Bis) |
| `3-3-2-grado-riesgo/` | 3.3.2 | Clasificación por grado de riesgo del cliente |
| `3-3-3-enr/` | 3.3.3 | Evaluación Nacional de Riesgos 2023 · 90 reactivos |
| `3-3-4-anticorrupcion/` | 3.3.4 | Guía Anticorrupción, Apartado III · 75 reactivos |

Cada herramienta trae arriba a la izquierda el botón «← Aula Módulo 3» para regresar al portal. El avance del simulador se guarda en el navegador de cada alumno, por herramienta.

## Para cambiar algo
- Ligas del portal: bloque `LIGAS` al inicio del `<script>` de `index.html`.
- Contenido de una herramienta: se corrige en su `datos.json` (en el proyecto de Claude) y se vuelve a armar; no se edita el HTML a mano.

GMC360 · 360Educa. Material de estudio; no sustituye la consulta de los textos oficiales.
