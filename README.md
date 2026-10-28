# lead-magnets

PDFs públicos que se entregan por DM de Instagram cuando alguien comenta la palabra clave
del reel correspondiente.

Se sirven vía CDN para que Meta pueda descargarlos con el `Content-Type` correcto:

```
https://cdn.jsdelivr.net/gh/facundogimenez-data/lead-magnets@main/<archivo>.pdf
```

| Archivo | Palabra clave | Reel |
|---|---|---|
| `repo-388-skills.pdf` | `REPO` | 388 skills de Claude Code: tres prompts para quedarte con doce |
| `prompt-excel-dashboard.pdf` | `PROMPT` | Del Excel al Dashboard: el prompt para el artefacto Dashboard de Claude (reel 05) |
| `contexto-claude-md.pdf` | `CONTEXTO` | **Reel 16** · Esto lo hace una carpeta de texto, no un plan de 200 dólares |
| `permisos-automatizaciones.pdf` | `PERMISOS` | **Reel 10 y 15** · Así termina el bot barato / lo que tu web cuenta a Google |
| `conectores-5-minutos.pdf` | `CONECTAR` | **Reel 11 y 17** · Conectar un MCP en 5 minutos / 4 herramientas para montarlo |
| `skills-negocio.pdf` | `SKILLS` | **Reel 12** · Las trece skills que uso para el trabajo de un negocio |
| `proceso-automatizable.pdf` | `CIERRE` | **Reel 13** · Los cuatro pasos del cierre de mes, conectados |
| `checklist-20-web.pdf` | `WEB` | **Reel 09** · Checklist de 20 puntos antes de publicar una web |

Los documentos se generan desde markdown con el script `md-to-pdf.mjs` del proyecto
`comment-to-dm`. Este repo solo publica el resultado.

— [@facugimenez.dev](https://instagram.com/facugimenez.dev) · [weautomate.es](https://weautomate.es)
