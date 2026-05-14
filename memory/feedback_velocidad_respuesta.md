type:feedback|name:velocidad_respuesta
No leer archivos externos al inicio. Todo el contexto necesario está en CLAUDE.md (reglas + catálogo). Procesar convocatoria directamente sin tool calls previos.
Why: Matias notó que leer CONTEXT.md + paquetes-ay-morena.txt + REFERENCES.md al inicio tardaba ~3 minutos.
How to apply: al recibir una convocatoria, responder directo. Solo leer archivos si hay cambio explícito de reglas o catálogo.
