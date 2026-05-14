# FORMAT — plantilla de salida exacta estilo Noelia

## ESTRUCTURA
```
*Vestuario extra*

*[DÍA EN MAYÚSCULAS]*

• *[Pack + Temática en formato natural]*
[Nombres] = traer [items separados por comas, "y" antes del último]
[Nombres] = traer [items]

• *[Siguiente evento]*
...

*[SIGUIENTE DÍA]*
...

⚠️ *Revisar:*
- [incertidumbre 1]
- [incertidumbre 2]
```

## REGLAS DE ESTILO
- Día: `*VIERNES 17 ABRIL*` (mayúsculas, entre asteriscos WhatsApp)
- Evento: `• *Pool party Perritos*` (bullet + asteriscos en nombre)
- Persona: `Maikel = traer short negro para piscina`
- Múltiples personas misma línea: `Susan, Ingrid = traer calsa corta`
- Varios items: `Felipe = traer pantalón negro de vestir, camisa negra, botines de vestir y cinturón`
- Si el extra aplica a todos del evento: `Todos = traer zapatos blancos y ropa interior extra`
- Si hay subgrupos: separar en líneas distintas

## NORMALIZACIÓN DE NOMBRES
- Respetar el nombre exactamente como aparece en la convocatoria
- Quitar sufijo Z de zanqueros al listar nombres (BrendaZ → Brenda) pero aplicar regla de zanquera

## AGRUPACIÓN
- Si una persona tiene el mismo extra en 2 eventos del mismo día → listar en ambos
- Si es un extra general del día (ej: todas calsa corta siempre) → poner 1 sola vez al inicio del día

## ABREVIATURAS PERMITIDAS (estilo Noelia real)
- "HRL" por "Hora Loca"
- "AM" por "Ay Morena"
- "Hrl" minúscula también válida
- "sáb"/"dom"/"vie" NO usar — siempre día completo

## EMOJIS
- ✅ Permitidos en notas propias: ⚠️
- ❌ No usar emojis decorativos salvo que Noelia los use (👠 🥾 👖 🩴)
- Si se usan, solo como refuerzo visual mínimo del item

## EJEMPLO OUTPUT COMPLETO

```
*Vestuario extra*

*VIERNES 17 ABRIL*

• *Pool party Perritos*
Todos = traer zapatos blancos y ropa interior extra
Maikel = traer short negro para piscina
Susan, Ingrid = traer calsa corta

• *HRL Boda Plateado Disco*
Laura, Ivonne = traer básica con cuello (el traje pica) y calsa corta
Felipe, Franco Vaca = traer polera negra, pantalón negro de vestir, botines de vestir y cinturón
Michelle, Wendy = traer calsa larga y básica (trajes de zanquera)
Niky, Nikol = traer básica con cuello y calsa corta (shots)

*SÁBADO 18 ABRIL*

• *Premium Mariposas*
Niky, Mariel, Noelia, Wendy = traer calsa corta

...

⚠️ *Revisar:*
- HRL Boda "PLATEADO DISCO" ambiguo: ¿Forever / Gemelas / Lentejuelas? Asumido lentejuelas.
- Teens TikTok Fútbol: no se indica árbitro, asumido Maikel por patrón histórico.
```

## CONDICIONES PARA OMITIR EVENTO
No generar línea de vestuario extra si:
- El evento es solo "SONIDO" o "SONIDO Y LUCES" sin animadores
- El evento es "ATRILES" sin rol activo
- Todos los extras del pack+temática+roles ya están cubiertos por el vestuario declarado (respetar provisto)
- No hay personal asignado (solo aparece "xxxx" o "pendiente")

En esos casos pasar al siguiente evento sin mencionar.
