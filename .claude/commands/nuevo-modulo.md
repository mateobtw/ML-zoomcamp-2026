---
description: Crea la carpeta de un módulo del curso y descarga su homework.md oficial
---

Quiero crear la carpeta del módulo: $ARGUMENTS

Sigue estos pasos exactamente:

1. Lee la tabla de la sección "Módulos del curso" en `CLAUDE.md` para resolver `$ARGUMENTS`
   (puede venir como número, ej. "2" o "02", o como slug, ej. "regression") al nombre de
   carpeta oficial con formato `NN-slug` (ej. `02-regression`).
2. Si `$ARGUMENTS` no corresponde a ningún módulo listado en la tabla (incluye el caso "07",
   que no tiene homework), avísame cuál es el problema y detente sin crear ni descargar nada.
3. Si la carpeta `NN-slug/` ya existe en la raíz del repo, avísame y detente sin sobrescribir
   nada.
4. Crea la carpeta `NN-slug/` en la raíz del repo.
5. Descarga el archivo oficial desde
   `https://raw.githubusercontent.com/DataTalksClub/machine-learning-zoomcamp/main/cohorts/2026/homework/NN-slug/homework.md`
   y guárdalo como `NN-slug/homework.md`. Por ahora solo ese archivo — nada de notebook ni
   datasets, eso se agrega después manualmente.
6. Confirma con un resumen corto (una o dos líneas) qué carpeta y archivo se crearon.
