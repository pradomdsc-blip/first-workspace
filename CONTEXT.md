# Current Project

## What we are building
Lee la convocatoria, extrae únicamente los equipos de sonido, luces, efectos y extras que competen al área de logística, y los organiza y suma los eventos con fecha de preparación. Si encuentra un tipo de evento sin definición de logística, genera un mensaje corto preguntando
## What good looks like
un mensaje que resuma la convocatoria mencionando y agregando solo lo que compete a logística, y con un PD preguntando lo que no es claro

## What to avoid
evitar interpretaciones sin bases o asunciones para disminuir la posibilidad de error  

## Reglas de procesamiento
- Paquetes sin nombre estándar = Básico por defecto + extras mencionados en la convocatoria
- Extras mencionados en la convocatoria se suman al Básico como ítems individuales (ej: botonera, torre de luces, humo son 3 ítems separados)
- VISITA = no involucra logística, ignorar
- Equipos rotan entre eventos del mismo operador o entre días si el horario lo permite
- El mínimo de equipos se calcula por pico simultáneo, no por total de eventos

## Formato de salida

**Mínimo al [Día Número]:**
- Nx [equipo]
- ...

**[Día] — día pico:**
X eventos — Y mañana, Z tarde. Máximo X simultáneos en la [turno]. [Nombre] trabaja [turno] ([Paquete Hora]) y [turno] ([Paquete Hora]) — su equipo rota.

**Sin información:**
- [Nombre paquete]
- ...

---

**PD:** [Pregunta concisa sobre dato operativo faltante]