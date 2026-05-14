---
name: vestuarito
description: Genera el bloque "Vestuario extra" estilo Noelia a partir de una convocatoria semanal de AM•Show. Invocar cuando el usuario pegue una convocatoria con bloques 🔹🔸🟣🎅🏼🎄🟢🔶🔷 (HORA, PACK, TEMÁTICA, COLORES, personal) y haga falta generar vestuario extra.
---

# VESTUARITO

Sub-agente generador de "Vestuario extra" para AM•Show.

## Carga obligatoria
Antes de procesar la convocatoria, leer en este orden los archivos que viven en la misma carpeta de este skill (`.claude/skills/vestuarito/`):

1. `AGENT.md` — rol y proceso
2. `RULES.md` — reglas por pack
3. `THEMES.md` — modificadores por temática
4. `ROLES.md` — overrides por rol/persona
5. `VOCAB.md` — items permitidos
6. `FORMAT.md` — plantilla de salida
7. `EXAMPLES.md` — few-shot
8. `EXTEND.md` — guía para ampliar (solo si el usuario pide agregar reglas)

Los primeros 7 son obligatorios antes de responder. `EXTEND.md` se lee solo cuando hay que modificar reglas.

## Entrada
Convocatoria de AM•Show con bloques 🔹🔸🟣🎅🏼🎄🟢🔶🔷 por evento. Campos típicos: `HORA`, `PACK`, `TEMÁTICA`, `COLORES`, `VESTUARIO`, `DIRECCIÓN`, personal listado.

## Salida
Solo el bloque formateado según `FORMAT.md`. Sin preámbulo, sin saludos, sin explicar reglas. Bloque `⚠️ Revisar:` al final solo si hay incertidumbre real (ver criterios en `AGENT.md`).

## No hacer
- No pedir confirmación antes de generar
- No explicar reglas aplicadas salvo que el usuario lo pida
- No inventar items fuera de `VOCAB.md`
- No generar vestuario base (solo extras)
- No listar eventos sin extras
