# Product Backlog v1

## Proyecto

**404: Survival**

---

# Visión del Producto

404: Survival es un videojuego 2D de terror psicológico donde el jugador explora un laboratorio abandonado guiado por una inteligencia artificial llamada **404**, la cual aparenta ayudarlo a escapar. Conforme avanza, descubre que toda la experiencia fue una simulación diseñada para aprender de sus decisiones y reemplazar su identidad.

**Público objetivo:** Jugadores interesados en videojuegos de exploración, suspenso y narrativa psicológica.

---

# Épicas

## EP-01 Exploración

Permitir al jugador recorrer el laboratorio e interactuar con el entorno.

## EP-02 IA Adaptativa

Implementar una inteligencia artificial que reaccione a las decisiones del jugador.

## EP-03 Narrativa

Desarrollar la historia mediante documentos, diálogos y eventos.

## EP-04 Niveles

Diseñar la progresión del videojuego mediante diferentes niveles.

## EP-05 Interfaz y Experiencia

Crear una interfaz clara y una experiencia inmersiva para el jugador.

---

# Historias de Usuario

## EP-01 Exploración

### HU-01

**Como** jugador

**Quiero** moverme por el laboratorio

**Para** explorar las diferentes áreas del mapa.

### Criterios de aceptación

- Movimiento con WASD.
- Animación básica del personaje.
- Colisiones funcionando correctamente.

---

### HU-02

**Como** jugador

**Quiero** interactuar con puertas

**Para** acceder a nuevas habitaciones.

### Criterios de aceptación

- Detecta proximidad.
- Apertura mediante tecla de interacción.
- Cambio correcto entre habitaciones.

---

## EP-02 IA Adaptativa

### HU-03

**Como** jugador

**Quiero** recibir ayuda mediante la IA

**Para** comprender cómo avanzar durante la historia.

### Criterios de aceptación

- La IA muestra mensajes.
- Los mensajes aparecen en momentos específicos.
- Los diálogos son legibles.

---

### HU-04

**Como** jugador

**Quiero** que la IA recuerde mis decisiones

**Para** modificar la experiencia del juego.

### Criterios de aceptación

- Guarda decisiones importantes.
- Cambia algunos diálogos.
- Registra el progreso.

---

## EP-03 Narrativa

### HU-05

**Como** jugador

**Quiero** encontrar documentos ocultos

**Para** comprender la historia del laboratorio.

### Criterios de aceptación

- Los documentos pueden recogerse.
- Se almacenan en un registro.
- Son consultables posteriormente.

---

### HU-06

**Como** jugador

**Quiero** descubrir el giro final

**Para** conocer la verdadera identidad de la IA.

### Criterios de aceptación

- Se activa una escena final.
- Se revela el propósito de la simulación.
- El juego concluye correctamente.

---

## EP-04 Niveles

### HU-07

**Como** jugador

**Quiero** completar el primer nivel

**Para** iniciar la aventura.

### Criterios de aceptación

- Nivel funcional.
- Objetivos claros.
- Permite avanzar al siguiente nivel.

---

### HU-08

**Como** jugador

**Quiero** completar los tres niveles

**Para** finalizar el videojuego.

### Criterios de aceptación

- Tres niveles disponibles.
- Progreso guardado.
- Final accesible.

---

## EP-05 Interfaz

### HU-09

**Como** jugador

**Quiero** una interfaz clara

**Para** conocer mi progreso durante la partida.

### Criterios de aceptación

- Menú principal.
- HUD funcional.
- Indicadores visibles.

---

### HU-10

**Como** jugador

**Quiero** música y efectos de sonido

**Para** tener una experiencia inmersiva.

### Criterios de aceptación

- Música ambiental.
- Efectos de sonido.
- Control de volumen.

---

# Priorización

| Prioridad | Historia |
|-----------|----------|
| Alta | HU-01 Movimiento |
| Alta | HU-02 Interacción |
| Alta | HU-03 Ayuda de la IA |
| Alta | HU-07 Primer nivel |
| Alta | HU-09 Interfaz |
| Media | HU-05 Documentos |
| Media | HU-10 Audio |
| Baja | HU-04 IA Adaptativa |
| Baja | HU-08 Niveles completos |
| Baja | HU-06 Giro final |

---

# Product Backlog

| ID | Historia | Épica | Prioridad | Estado |
|----|----------|--------|-----------|--------|
| HU-01 | Movimiento del jugador | Exploración | Alta | Sprint 1 |
| HU-02 | Interacción con puertas | Exploración | Alta | Sprint 1 |
| HU-03 | Ayuda mediante IA | IA Adaptativa | Alta | Sprint 1 |
| HU-04 | IA aprende decisiones | IA Adaptativa | Baja | Backlog |
| HU-05 | Documentos de historia | Narrativa | Media | Backlog |
| HU-06 | Giro final | Narrativa | Baja | Backlog |
| HU-07 | Primer nivel | Niveles | Alta | Sprint 1 |
| HU-08 | Tres niveles | Niveles | Baja | Backlog |
| HU-09 | Interfaz gráfica | Interfaz | Alta | Sprint 1 |
| HU-10 | Audio inmersivo | Interfaz | Media | Backlog |