# EXTEND — cómo agregar información nueva

## AGREGAR TEMÁTICA NUEVA
Abrir `THEMES.md`, agregar línea:
```
NOMBRE_TEMATICA :: mod_chicas | mod_chicos | mod_universal | notas
```
Usar `=` para heredar de otra: `NUEVA :: = PRINCESAS`
Sumar con `+`: `NUEVA :: calsa_corta + basica`

## AGREGAR PACK NUEVO
Abrir `RULES.md`, formato:
```
NUEVO_PACK :: chicas | chicos | universal | roles
```

## AGREGAR PERSONA NUEVA
Abrir `ROLES.md`, sección PERSONAS:
```
PERSONA_Nombre :: si_CONDICION_extra + si_OTRA_extra
```

## AGREGAR ITEM NUEVO AL VOCABULARIO
Abrir `VOCAB.md`:
```
nuevo_item = "texto literal que se va a usar"
```
Solo agregar si aparece repetido ≥3 veces en reglas reales.

## AGREGAR EMPRESA CORPORATIVA NUEVA
Abrir `ROLES.md` al final, en la lista de "ZONAS PROTEGIDAS":
```
NOMBRE_EMPRESA → vestuario corporativo respetado, solo agregar zapatos_blancos + polera_morada_AM(backup)
```

## AGREGAR REGLA CASO ESPECIAL
Si una temática + pack específico tiene una excepción, agregar en `RULES.md` con prefijo `EXCEPCION_`:
```
EXCEPCION_HRL_BODA_VINTAGE :: override → 40_antifaces_provistos + ropa_elegante_negro
```

## ACTUALIZAR TRAS UN EVENTO REAL
Proceso:
1. Al terminar semana, revisar qué "Vestuario extra" publicó Noelia realmente
2. Comparar con lo que generó el agente
3. Si hay diferencia → editar `THEMES.md` o `ROLES.md` según corresponda
4. Si la diferencia es por una temática nueva → agregarla
5. Si es por una persona nueva → agregarla en `PERSONA_`

## PRIORIDAD DE REGLAS
Cuando hay conflicto, ganan en este orden:
1. `VESTUARIO:` declarado explícito en convocatoria
2. `EXCEPCION_*` en RULES.md
3. Rol de persona específico (PERSONA_*)
4. Rol genérico (ARBITRO, ZANQUERO, BOTARGA, etc.)
5. Modificador de temática (THEMES.md)
6. Regla base del pack (RULES.md)
7. Default "todos zapatos blancos" si nada aplica

## LIMPIAR / VERIFICAR
Cada 2-3 meses revisar:
- Items en VOCAB.md con conteo de uso — eliminar los que no se usaron
- Temáticas en THEMES.md que no aparecieron → evaluar si borrar
- Personas en ROLES.md que ya no están en el equipo → borrar

## FORMATO DE NOTAS AL PIE
En cualquier archivo, comentarios con `#` al inicio de línea. NO usar `//` ni `<!--`.
