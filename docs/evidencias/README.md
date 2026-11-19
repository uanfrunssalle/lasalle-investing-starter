# Evidencias de ejecución

Cada evidencia lleva la fecha en el nombre. Se guardan las respuestas reales obtenidas, sin editar.

| Fecha | Fichero | Qué demuestra |
|---|---|---|
| 2026-11-19 | `2026-11-19_api_base.json` / `.headers.txt` | Paso 4.1 C: la API base arranca en local y `GET /api/predictions` devuelve HTTP 200 con nueve selecciones. Dos consultas seguidas devuelven exactamente el mismo contenido y `generated_at`. Todavía con el nombre de ejemplo. |
| 2026-11-19 | `2026-11-19_health_base.json` | `GET /api/health` responde `ok` con el artefacto incluido. |

Comprobaciones previas del mismo día: `uv sync --locked --python 3.11` correcto y `uv run pytest -q` → 6 passed.
