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
   y guárdalo como `NN-slug/homework.md`.
6. Lee ese `homework.md` y busca los datasets que pide (normalmente aparecen como un link de
   descarga o un comando `wget` apuntando a
   `https://raw.githubusercontent.com/DataTalksClub/machine-learning-zoomcamp/main/cohorts/2026/data/<archivo>`).
   Encuentra **todos** los que se mencionen (puede haber más de uno).
7. Si encuentras uno o más datasets, crea `NN-slug/data/` y descarga cada archivo ahí
   (`NN-slug/data/<archivo>`), conservando el nombre original del archivo.
8. No crees notebook — eso se agrega después manualmente.
9. Confirma con un resumen corto (unas pocas líneas) qué carpeta, `homework.md` y datasets se
   crearon. Si `homework.md` no menciona ningún dataset descargable, dilo explícitamente en el
   resumen en vez de asumir que no hace falta nada.
10. Siempre, después del resumen, explícame brevemente de qué va el deber (basándote en el
    `homework.md` que acabas de leer, sin resolver nada):
    - De qué trata en 2 o 3 frases y qué se practica en este módulo.
    - Qué pide cada pregunta, en una línea cada una (Q1, Q2, ...), sin dar respuestas ni
      resultados.
    - Cómo se relaciona con los módulos anteriores (mismo dataset, mismas técnicas, qué
      cambia).
    - Si requiere algo especial: librerías o herramientas que instalar (ej. `xgboost`, `uv`,
      Docker), o que no se resuelve en notebook.
    Mantenlo corto y en español; es una orientación previa, no una guía de solución.
