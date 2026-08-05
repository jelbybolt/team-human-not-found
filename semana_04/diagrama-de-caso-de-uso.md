# Diagrama de Caso de Uso

**Proyecto:** 404: SURVIVAL

**Equipo:** Human not Found

**Fecha:** 04/08/2026

## Diagrama



### Actores

- Jugador
- IA 404

### Casos de uso principales

- Iniciar partida
- Configurar opciones
- Explorar laboratorio
- Mover personaje
- Interactuar con objetos
- Abrir puertas
- Recibir instrucciones de la IA
- Resolver acertijos
- Evitar amenazas
- Completar nivel
- Guardar progreso
- Cargar partida
- Salir del juego

### Casos de uso de la IA

- Proporcionar instrucciones
- Mostrar mensajes
- Adaptar comportamiento según las decisiones del jugador

### Relaciones

#### <<include>>

- Explorar laboratorio → Mover personaje
- Explorar laboratorio → Interactuar con objetos
- Interactuar con objetos → Abrir puertas
- Completar nivel → Resolver acertijos
- Completar nivel → Explorar laboratorio
- Completar nivel → Iniciar partida
- Completar nivel → Cargar primer nivel

#### <<extend>>

- Recibir instrucciones de la IA → Explorar laboratorio
- Evitar amenazas → Explorar laboratorio
- Guardar progreso → Explorar laboratorio
- Completar nivel → Adaptar comportamiento
- Proporcionar instrucciones → Recibir instrucciones de la IA