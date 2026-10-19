# Exámenes de pregrado

Sitio único para los exámenes en línea de pregrado (Facultad de Medicina, UNAM — sede CMN "20 de Noviembre").
Publicado con GitHub Pages: https://moymaa.github.io/examenes-pregrado/

## Estructura

Una carpeta por examen; cada carpeta es autocontenida y conserva su propio backend de Apps Script y su propia hoja de cálculo.

| Carpeta | Examen | Estado |
|---|---|---|
| `medpsico-u1u2/` | Medicina Psicológica y Comunicación, Unidades 1-2 (ago-2026) | cerrado |
| `medpsico-u3u5/` | Medicina Psicológica y Comunicación, Unidades 3-5, examen intermedio (viernes 23-oct-2026, 15:00-18:00; se anuncia cierre a las 17:00) | programado |

## Reglas

- El repositorio es **público** porque GitHub Pages no sirve repositorios privados con el plan actual: las preguntas de un examen no deben quedar en el HTML en claro (usar imágenes y, de preferencia, cifrado por caso como en `examenes-residencia/genetica`).
- La clave de respuestas vive **solo** en el backend de Apps Script, nunca aquí.
- Un examen = su propio proyecto de Apps Script y su propia hoja. El backend es append-only: nunca se borran respuestas de alumnos.
- Los repositorios originales `moymaa/examen-medpsico` y `moymaa/examen-genetica` se conservan como archivo; las aplicaciones ya cerradas siguen resolviendo en sus URL antiguas.
