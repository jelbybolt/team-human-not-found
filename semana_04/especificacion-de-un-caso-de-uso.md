# Especificación de Caso de Uso

## CU-03 – Explorar laboratorio

| Campo | Descripción |
|--------|-------------|
| **Nombre** | Explorar laboratorio |
| **Identificador** | CU-03 |
| **Actor principal** | Jugador |
| **Actor secundario** | IA 404 |
| **Objetivo** | Permitir que el jugador explore las diferentes áreas del laboratorio para avanzar en la historia, interactuar con el entorno, descubrir información y desbloquear nuevas zonas del videojuego. |
| **Prioridad** | Alta |

---

## Precondiciones

- El jugador ha iniciado una partida.
- El laboratorio ha sido cargado correctamente.
- El personaje se encuentra disponible para ser controlado.
- El sistema opera con normalidad.

---

## Flujo principal

1. El jugador inicia la exploración del laboratorio.
2. El sistema carga el escenario.
3. El jugador mueve al personaje por las distintas áreas.
4. El jugador interactúa con los objetos del entorno.
5. El sistema procesa la interacción y muestra el resultado.
6. El jugador abre puertas para acceder a nuevas zonas cuando corresponde.
7. El sistema actualiza el progreso del jugador.
8. El jugador continúa la exploración hasta alcanzar el siguiente objetivo.

---

## Flujos alternativos

### FA-01: Recibir instrucciones de la IA

- La IA 404 detecta que el jugador necesita orientación.
- El sistema presenta una instrucción contextual.
- El jugador continúa explorando.

### FA-02: Evitar amenazas

- Se detecta una amenaza durante la exploración.
- El jugador la esquiva o toma una ruta alternativa.
- La exploración continúa.

### FA-03: Guardar progreso

- El jugador selecciona **Guardar progreso**.
- El sistema almacena el estado actual de la partida.
- El jugador continúa explorando.

---

## Relaciones con otros casos de uso

### <<include>>

- Mover personaje
- Interactuar con objetos
- Abrir puertas

### <<extend>>

- Recibir instrucciones de la IA
- Evitar amenazas
- Guardar progreso

---

## Postcondiciones

### Si finaliza correctamente

- Se actualiza el progreso del jugador.
- Se habilita la continuación de la exploración.
- El estado del escenario refleja las acciones realizadas.

### Si no finaliza correctamente

- El progreso previo se conserva.
- El jugador puede reanudar la exploración posteriormente.