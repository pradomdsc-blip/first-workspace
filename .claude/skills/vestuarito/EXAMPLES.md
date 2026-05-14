# EXAMPLES — convocatorias reales con output esperado
# Usar como few-shot para consistencia. Extraídos del chat histórico.

## EJEMPLO 1
### INPUT
```
*SÁBADO 22 DE MARZO*
🔸3) 21:00 RECEPCIÓN + HRL
EVENTO: 15 AÑOS
VESTUARIO: NEGROS CON COLAS
DIRECCIÓN: CLUB DE TENNIS
21:00 hra - Recepción: Niky Britany
23:30 - HRL: Niky Susan Britany Felipe MathiasPaz
Zanqueros: Michelle Brenda (plateados)
```
### OUTPUT
```
• *Recepción + HRL 15 años Negros con colas*
Niky, Britany = traer calsa blanca y calsa corta
Niky, Britany, Susan = traer calsa corta
Felipe, Mathias Paz = traer zapatos de vestir negro y polera negra
Michelle, Brenda = traer calsa larga (zanqueras plateadas)
```

## EJEMPLO 2
### INPUT
```
*MIERCOLES 18 DIC*
🔸1) 13:00/18:00 PACK ESPECIAL
TEMÁTICA: POOL PARTY
DIRECCION: FRATERNIDAD FLOJONAZOS
*Vestuario Sport para piscina*
Gustavo Ivonne Laura Maickel Sandra Brenda
```
### OUTPUT
```
• *Pack especial Pool party*
Todos = traer ropa interior extra, calzado adecuado para piscina y zapatos blancos
Maickel = traer short negro para piscina
Ivonne, Laura, Sandra, Brenda = traer calsa corta
```

## EJEMPLO 3
### INPUT
```
🔹1) 09:00/11:00 CORPORATIVO
EMPRESA: CBN
TEMÁTICA: COPA MALTIN
VESTUARIO: SPORT
EDGAR BRUNO Maickel nikol Niky Susan Noelia
```
### OUTPUT
```
• *Corporativo CBN Copa Maltin*
Todos = traer polera morada de Ay Morena, jogger negro y zapatos blancos
```

## EJEMPLO 4
### INPUT
```
🔸1) 16:00/20:00 MASTER LED
TEMATICA: GRANJA DE ZENÓN
DIRECCIÓN: MONTERO
*Vaca Loca - Zenón*
RILVER Laura Maikel Romina LuísZ BrendaZ
```
### OUTPUT
```
• *Master LED Granja de Zenón*
Laura, Romina = traer calsa blanca, molecas, básica y ropa negra para el show led
Maikel = traer pantalón jeans azul, botines café, cinturón y ropa negra para el show led
Luís = traer pantalón jeans azul, cinturón y ropa para sudar (botarga Zenón o Bartolito)
Brenda = traer calsa larga y básica (zanquera)
```

## EJEMPLO 5
### INPUT
```
🔸 *00:00* HRL ADULTOS
EVENTO: BODA
TEMÁTICA: ECUADOR - BOLIVIA
VESTUARIO: PLATEADOS
DIRECCIÓN: HOTEL LOS TAJIBOS
• Ecuador: Susan Laura Noelia Maikel
• Bolivia: Niky Mathias Majo Gustavo
• Host: Ivonne nikol
```
### OUTPUT
```
• *HRL Adultos Boda Ecuador - Bolivia (Plateados)*
Susan, Laura, Noelia, Niky, Majo = traer básica con cuello y calsa corta
Maikel, Mathias, Gustavo = traer polera negra, pantalón negro de vestir, botines de vestir y cinturón
Ivonne, Nikol = traer básica con cuello y calsa corta (hosts, usan lentejuelas)
```

## EJEMPLO 6 — VESTUARIO DECLARADO QUE SOBREESCRIBE
### INPUT
```
🔸1) 10:00 - 17:30 / ESPECIAL
TEMATICA: PISCINA Y TRAJES TIPICOS
DIRECCIÓN: RIO SELVA RESORT
*Juegos pool party*
Rilver Shirley darling Ingrid
```
### OUTPUT
```
• *Especial Piscina y trajes típicos (Río Selva)*
Todos = traer ropa interior extra, chinelas o chocs y zapatos blancos
Shirley, Darling, Ingrid = traer calsa corta
```

## EJEMPLO 7 — SHOW DISNEY CON BOTARGAS
### INPUT
```
🔹3) 16:30/19:30 SHOW DISNEY
TEMÁTICA: MICKEY Y SUS AMIGOS
VESTUARIO: DISNEY
Felipe - Mickey
Wendy - Minnie
Matías Prado - pato
Sofía - pata
Lucho - Goofy
Bailarines: Mariel Maikel Majo Mathias Paz
```
### OUTPUT
```
• *Show Disney Mickey y sus amigos*
Felipe, Matías Prado, Lucho = traer polera morada de Ay Morena, jogger negro y ropa para sudar (botargas)
Wendy, Sofía = traer polera morada de Ay Morena, calsa negra y ropa para sudar (botargas)
Mariel, Majo = traer calsa corta (bailarinas)
Maikel, Mathias Paz = traer zapatos de vestir negro y pantalón (bailarines)
```

## EJEMPLO 8 — EVENTO PROTEGIDO (no genera extras adicionales)
### INPUT
```
🎅🏼2) 19:00/22:00 PAPÁ NOEL C/TRINEO
EMPRESA: TIGO
DIRECCIÓN: TIGO KM9
BRUNO EDGAR Mariel Matías Prado
```
### OUTPUT
```
• *Papá Noel con trineo TIGO*
Traje de Papá Noel y asistentes provistos por AM. Todos = traer zapatos blancos.
```

## EJEMPLO 9 — BABY SHOWER
### INPUT
```
🔸2)16:00-19:00/ BABY SHOWER
TEMÁTICA: OSITA
COLORES: ROSA
Xander Luz Nikol
```
### OUTPUT
```
• *Baby shower Osita*
Luz, Nikol = traer pantalón de vestir blanco y tacos (coordinar modelo y color)
```

## EJEMPLO 10 — VENTURA / MANUALIDADES
### INPUT
```
🔹3) 16:00/19:00 MANUALIDADES
VESTUARIO: NAVIDEÑOS
DIRECCIÓN: VENTURA MALL
Edgar Gisselle Luz simone
```
### OUTPUT
```
• *Ventura Mall Manualidades navideños*
Gisselle, Luz, Simone = traer calsa blanca y calsa corta (van de cascanueces antiguo)
```
