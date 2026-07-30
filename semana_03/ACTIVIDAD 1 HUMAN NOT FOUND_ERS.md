**Ingeniería de Software 2 · TS359**

**Especificación de Requerimientos de Software (ERS)**

**Nombre del proyecto:** 404: Survival

**Equipo / Integrantes:** Human not Found

**Fecha:** 28/07/2026

**Versión del documento:** 1.0

# **1. Introducción**

## **1.1 Propósito**

Este documento describe los requerimientos funcionales y no funcionales
del videojuego 404: Survival, un título 2D de terror psicológico. Sirve
como referencia principal para el equipo de desarrollo durante las fases
de diseño, construcción y pruebas, garantizando que todas las partes
interesadas tengan una comprensión clara y unificada de lo que se debe
construir.

## **1.2 Alcance**

El sistema cubre una experiencia de un jugador que explora un
laboratorio abandonado, interactúa con el entorno y recibe instrucciones
de una inteligencia artificial (IA), incluye tres niveles de progresión,
una narrativa con giro argumental y una interfaz de usuario básica.
Quedan fuera del alcance de esta versión: el modo multijugador en línea,
la personalización avanzada y la integración con plataformas externas de
distribución.

## **1.3 Definiciones, acrónimos y abreviaturas**

Rf: Requerimiento Funcional .

RNF: Requerimiento No Funcional.

IA: Inteligencia Artificial (Personaje 404).

NPC: Non-Player Character (Personaje no jugador).

HUD: Heads-Up Display (Interfaz visual durante el juego).

MoSCoW: Método de priorización (Must have, Should have, Could have,
Won’t have).

Sprint: Iteración de desarrollo dentro de la metodología Scrum.

# **2. Descripción general**

## **2.1 Perspectiva del producto**

404: Survival es un videojuego 2D independiente, desarrollado desde cero
y diseñado para ser jugable en navegador web o como aplicación de
escritorio. No depende de otros sistemas existentes y constituye un
producto completo por sí mismo.

## **2.2 Funciones principales del producto**

- Permitir al jugador moverse y explorar el laboratorio.

- Gestionar la interacción con objetos del entorno (puertas,
  documentos).

- Mostrar mensajes y diálogos de la IA (Personaje 404).

- Implementar un sistema de progresión de tres niveles.

- Proporcionar una interfaz gráfica funcional (menú principal, HUD).

- Almacenar decisiones clave para modificar la experiencia del jugador.

## **2.3 Características de los usuarios**

Jugadores casuales interesados en videojuegos de exploración, suspenso y
narrativa psicológica, con edades comprendidas entre 12 y 30 años. No
requieren de conocimientos técnicos previos; se espera que tengan
familiaridad básica con controles de teclado (WASD, teclas de
interacción).

## **2.4 Restricciones**

- El desarrollo se realizará en un período académico de aproximadamente
  16 semanas, organizado en sprints de 2 semanas.

- El equipo está compuesto por 6 estudiantes sin experiencia profesional
  previa en desarrollo de videojuegos.

- Los recursos técnicos se limitan a herramientas gratuitas o de código
  abierto (Godot, Unity Personal, Git, Github).

- El juego debe ser jugable en hardware de gama media sin requerir
  conexión a internet (excepto para descarga).

# **3. Requerimientos específicos**

## **3.1 Requerimientos funcionales (RF)**

| **ID** | **Descripción del requerimiento**                                                                                                                                          | **Tipo (Usuario / Sistema)** | **Prioridad (MoSCoW)** |
|--------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------|------------------------|
| RF-01  | El sistema debe permitir al jugador moverse por el laboratorio utilizando las teclas WASD, con animación básica y colisiones funcionales.                                  | Sistema                      | Must have              |
| RF-02  | El sistema debe detectar la proximidad del jugador a las puertas y permitir su apertura mediante una tecla de interacción (E), cambiando correctamente entre habitaciones. | Sistema                      | Must have              |
| RF-03  | El sistema debe mostrar mensajes de la IA (personaje 404) en momentos clave de la historia para guiar al jugador.                                                          | Sistema                      | Must have              |
| RF-04  | El sistema debe permitir al jugador iniciar una partida desde un menú principal y visualizar su progreso mediante un HUD funcional (vida, nivel, objetivos)                | Usuario                      | Must have              |
| RF-05  | El sistema debe permitir al jugador completar tres niveles progresivos, guardando el avance entre ellos y mostrando una escena final con el giro argumental.               | Usuario                      | Should have            |

## **3.2 Requerimientos no funcionales (RNF)**

| **ID** | **Descripción del requerimiento**                                                                                                   | **Categoría**  | **Prioridad (MoSCoW)** |
|--------|-------------------------------------------------------------------------------------------------------------------------------------|----------------|------------------------|
| RNF-01 | El juego debe cargar cada nivel en menos de 3 segundos en un dispositivo de gama media (procesador intel i5, 8 GB RAM).             | Rendimiento    | Must have              |
| RNF-02 | La interfaz de usuario debe ser clara, legible y funcional en resoluciones de pantalla de 1280x720 píxeles o superiores.            | Usabilidad     | Should have            |
| RNF-03 | El sistema debe funcionar sin errores críticos (caídas, pérdida de progreso) durante al menos 30 minutos de juego continuo.         | Fiabilidad     | Should have            |
| RNF-04 | El código fuente documentado en inglés y seguir estándares de nomenclatura definidos por el equipo para facilitar el mantenimiento. | Mantenibilidad | Should have            |

# **4. Casos de uso / Historias de usuario asociadas**

**Historia asociada a: RF-01 (Movimiento del jugador)**

Como jugador,  
Quiero moverme por el laboratorio usando WASD,  
Para explorar las diferentes áreas del mapa.

**Criterios de aceptación:**

- Dado que el jugador inicia el nivel, cuando presiona las teclas WASD,
  entonces el personaje se mueve en la dirección correspondiente.

- Dado que el personaje se mueve, cuando choca contra una pared u objeto
  sólido, entonces se detiene sin atravesarlo.

- Dado que el personaje se desplaza, cuando se mueve, entonces se
  reproduce una animación básica de caminata.

**Historia asociada a: RF-02 (Interacción con puertas)**

Como jugador,  
Quiero interactuar con las puertas presionando E,  
Para acceder a nuevas habitaciones.

**Criterios de aceptación:**

- Dado que el jugador está cerca de una puerta, cuando se muestra un
  indicador de interacción, entonces al presionar E la puerta se abre.

- Dado que la puerta se abre, cuando el jugador atraviesa el umbral,
  entonces la escena cambia a la nueva habitación.

- Dado que el jugador está lejos de la puerta, cuando presiona E,
  entonces no ocurre ninguna acción.

**Historia asociada a: RF-03 (Mensajes de la IA)**

Como jugador,  
Quiero recibir ayuda mediante la IA,  
Para comprender cómo avanzar durante la historia.

**Criterios de aceptación:**

- Dado que el jugador alcanza un punto clave del nivel, cuando la IA
  envía un mensaje, entonces aparece un cuadro de diálogo en pantalla.

- Dado que el mensaje se muestra, cuando el jugador presiona una tecla,
  entonces el diálogo se cierra y el juego continúa.

- Dado que hay múltiples mensajes, cuando se despliegan, entonces son
  legibles y tienen un estilo visual coherente.

**Historia asociada a: RF-04 (Menú principal y HUD)**

Como jugador,  
Quiero una interfaz clara,  
Para conocer mi progreso durante la partida.

**Criterios de aceptación:**

- Dado que el jugador inicia el juego, cuando aparece el menú principal,
  entonces se muestran opciones para "Nueva partida", "Cargar partida" y
  "Salir".

- Dado que el jugador está en partida, cuando el HUD está visible,
  entonces muestra nivel actual, objetivos y otros indicadores
  relevantes.

- Dado que el jugador avanza, cuando se actualiza el progreso, entonces
  el HUD refleja los cambios inmediatamente.

**Historia asociada a: RF-05 (Tres niveles y final)**

Como jugador,  
Quiero completar los tres niveles,  
Para finalizar el videojuego y descubrir el giro final.

**Criterios de aceptación:**

- Dado que el jugador completa el nivel 1, cuando avanza, entonces se
  desbloquea el nivel 2.

- Dado que el jugador completa el nivel 2, cuando avanza, entonces se
  desbloquea el nivel 3.

- Dado que el jugador completa el nivel 3, cuando se activa la escena
  final, entonces se revela el propósito de la simulación y el juego
  concluye correctamente.

# **5. Criterios de aceptación generales del producto**

El producto (incremento de Sprint 1) se considerará completo y listo
para entrega cuando se cumplan las siguientes condiciones:

1.  Todos los RF marcados como **Must have** están implementados y
    probados sin errores críticos.

2.  El juego permite iniciar una partida, moverse, interactuar con
    puertas, recibir mensajes de la IA y completar el primer nivel.

3.  La interfaz de usuario (menú principal, HUD) funciona correctamente
    y es legible.

4.  Los criterios de aceptación de cada historia de usuario priorizada
    han sido verificados y aprobados por el Product Owner.

5.  No existen errores que impidan el flujo principal del juego (caídas,
    pérdida de progreso, controles no responsivos).

# **6. Historial de revisiones**

| **Fecha**  | **Versión** | **Autor(es)**                                                      | **Descripción del cambio**                                                        |
|------------|-------------|--------------------------------------------------------------------|-----------------------------------------------------------------------------------|
| 28/07/2026 | 1.0         | William S., Selvin A., Byron S., Yaxchel X., Hab'il X., Natalia C. | Creación inicial del documento basado en el Product Backlog v1 y roles definidos. |
|            |             |                                                                    |                                                                                   |
