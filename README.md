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

Los documentos se generan desde markdown con el script `md-to-pdf.mjs` del proyecto
`comment-to-dm`. Este repo solo publica el resultado.

— [@facugimenez.dev](https://instagram.com/facugimenez.dev) · [weautomate.es](https://weautomate.es)
