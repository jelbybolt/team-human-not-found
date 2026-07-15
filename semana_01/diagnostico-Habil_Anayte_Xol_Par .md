Actuar como un evaluador de ingeniería de software. Voy a comenzar el curso IS2 y quiero saber que tan sólidos son mis conocimientos de IS1. Hazme 5 preguntas de diagnóstico sobre los siguientes temas: 
1. Ciclo de vida del software
2. Requerimientos funcionales y no funcionales. 
3. Diagramas UML (clases y casos de uso)
4. Diseño de software
5. Proceso de desarrollo y metodologías. 
Hazme las preguntas de una en una y espera mi respuesta antes de continuar. Al final evalúa mis repuestas, indica que estuvo correcto e incompleto, identifica mis 3 fortalezas principales y dame un plan de 3 acciones concretas para reforzar mis debilidades antes de la próxima clase.
Perfecto. Actuaré como si estuviera realizando una evaluación diagnóstica para un estudiante que está por iniciar Ingeniería de Software II. No solo evaluaré si la respuesta es correcta, sino también la profundidad del razonamiento y el uso adecuado de conceptos.
Haré 5 preguntas, una por una, y esperaré tu respuesta antes de pasar a la siguiente. Al finalizar, te daré:
•	Una evaluación general de tu nivel de IS1.
•	Qué estuvo correcto y qué estuvo incompleto en cada respuesta.
•	Tus 3 fortalezas principales.
•	Un plan de 3 acciones concretas para prepararte antes de IS2.
Comencemos.
Pregunta 1: Ciclo de vida del software
Imagina que una empresa quiere desarrollar un sistema para administrar una biblioteca universitaria.
Pregunta:
Describe las principales fases del ciclo de vida del software y explica brevemente qué se realiza en cada una. Además, menciona qué problemas podrían surgir si se omite la fase de pruebas.
Tómate el tiempo que necesites. Cuando respondas, evaluaré tu respuesta y luego pasaré a la siguiente pregunta.
1. Planificación: es el proceso en el que se hace un análisis de los requerimientos, costos, infraestructura en la que se va a trabajar, las necesidades, viabilidad, obstáculos que pueden surgir para la planificación del desarrollo. Por ejemplo qué tan buena es la organización de los libros en términos de ordenamiento según un sistema escalable, cómo se lleva a cabo la recolección de datos de préstamos y devoluciones. 
2. Diseño. En este paso según nuestros requerimientos y análisis se hace un prototipo de diseño, un diagrama, un dibujo tanto de los requerimientos del sistema, la plataforma de interacción del usuario y así mismo el de la base de datos. 
3. Implementación. En la implementación empieza el desarrollo de la plataforma, cómo se dividen las tareas, en qué entregables se realiza. 
4. Pruebas. En la fase de pruebas es importante tener en cuenta si está funcionando, tener feedback del cliente, del usuario, encontrar las ventajas y fallas del software para mejoras que prevengan cualquier falla
5. Despliegue. Se implementa de forma segura ya probado el software para el uso de la biblioteca
Gracias. Esta es mi evaluación de tu primera respuesta.
Lo que estuvo correcto:
•	Identificaste correctamente las fases principales del ciclo de vida: planificación, diseño, implementación, pruebas y despliegue.
•	Explicaste con claridad el propósito general de cada fase.
•	Relacionaste la planificación con un caso concreto (la biblioteca), lo que demuestra que entiendes que los requerimientos nacen del problema de negocio y no solo del software.
•	En la fase de pruebas mencionaste aspectos importantes como la validación, la retroalimentación del usuario y la detección de errores.
Lo que estuvo incompleto o podría mejorar:
•	En la planificación mezclaste actividades de levantamiento de requerimientos con análisis de factibilidad. No está mal, pero habría sido útil distinguirlas. Normalmente se habla de:
o	Levantamiento y análisis de requerimientos.
o	Estudio de factibilidad (técnica, económica y operativa).
o	Planificación del proyecto.
•	En la fase de diseño faltó mencionar que se define la arquitectura del sistema, los componentes, las interfaces y las decisiones técnicas, además del diseño de la base de datos y la interfaz.
•	En implementación habría sido bueno mencionar la codificación, integración de módulos y control de versiones.
•	En despliegue faltó incluir actividades como instalación, configuración, capacitación de usuarios y mantenimiento inicial.
•	La pregunta pedía explicar qué problemas surgirían si se omite la fase de pruebas, y esa parte quedó implícita pero no respondida directamente. Una respuesta completa habría mencionado consecuencias como:
o	errores en producción,
o	vulnerabilidades de seguridad,
o	incumplimiento de requerimientos,
o	pérdida de confianza de los usuarios,
o	mayores costos de corrección.
Evaluación de esta pregunta: 8.5/10
Se nota una buena comprensión conceptual. Lo que te falta es usar una terminología un poco más precisa y cubrir algunos detalles que suelen evaluarse en cursos universitarios de Ingeniería de Software.
Ahora pasemos a la siguiente.
Pregunta 2: Requerimientos funcionales y no funcionales
Supón que desarrollarás un sistema para una clínica médica donde los pacientes pueden reservar citas en línea.
Pregunta:
1.	Explica con tus propias palabras la diferencia entre un requerimiento funcional y uno no funcional.
2.	Escribe tres ejemplos de requerimientos funcionales y tres ejemplos de requerimientos no funcionales para este sistema.
Un requerimiento funcional es el que se define según el caso de uso por ejemplo el que se pueda ingresar los datos del paciente, que las reservas de citas permitan tener hora, fecha y detalles principales del paciente, que la plataforma sea intuitiva, que pueda generarse un ticket o comprobante de cita, Un requerimiento no funcional es aquel que surge ya en la implementación técnica, por ejemplo el garantizar que la plataforma tenga https, que el sistema pueda estar disponible 24/7, implementar una mitigación de riesgos cuando la base de datos falle y tener alguna herramienta de auditoría ya que es primordial para que los pacientes puedan registrarse y reservar citas para una clínica médica
Gracias. Esta respuesta muestra que entiendes bastante bien la diferencia general, aunque hay un detalle importante que conviene corregir antes de IS2.
Lo que estuvo correcto:
•	Identificaste correctamente varios requerimientos funcionales relacionados con lo que el sistema debe hacer.
•	Los ejemplos de seguridad (HTTPS), disponibilidad 24/7 y recuperación ante fallos son buenos ejemplos de requerimientos no funcionales.
•	Relacionaste los requerimientos con el contexto de una clínica, lo cual es una buena práctica.
Lo que estuvo incompleto o necesita corrección:
•	Dijiste que un requerimiento no funcional "surge ya en la implementación técnica". Esa afirmación no es del todo correcta. Los requerimientos no funcionales también se definen desde la etapa de análisis junto con los funcionales, porque forman parte de las necesidades del sistema. La diferencia no es cuándo aparecen, sino qué describen.
o	Los funcionales describen qué hace el sistema.
o	Los no funcionales describen cómo debe comportarse el sistema o qué restricciones debe cumplir (rendimiento, seguridad, disponibilidad, usabilidad, mantenibilidad, etc.).
•	Uno de tus ejemplos funcionales fue: "que la plataforma sea intuitiva". Ese realmente es un requerimiento no funcional, porque describe una característica de usabilidad y no una funcionalidad.
Una clasificación más precisa de tus ejemplos sería:
Funcionales:
•	Registrar pacientes.
•	Reservar citas indicando fecha y hora.
•	Generar un comprobante o ticket de la cita.
No funcionales:
•	La plataforma debe ser intuitiva (usabilidad).
•	Debe utilizar HTTPS (seguridad).
•	Debe estar disponible 24/7 (disponibilidad).
•	Debe recuperarse ante fallos de la base de datos (confiabilidad).
Evaluación de esta pregunta: 8/10
Tu comprensión es buena. El principal punto a reforzar es aprender a distinguir claramente las funcionalidades de los atributos de calidad del sistema. Esa diferencia aparece constantemente en Ingeniería de Software II, especialmente cuando se habla de arquitectura y diseño.
Ahora continuemos.
Pregunta 3: Diagramas UML (Clases y Casos de Uso)
Imagina un sistema de biblioteca donde:
•	Un Usuario puede pedir prestado varios Libros.
•	Cada Libro pertenece a una Categoría.
•	Un Bibliotecario registra los préstamos y las devoluciones.
Sin dibujar el diagrama, responde:
1.	¿Qué clases incluirías en un diagrama de clases y cuáles serían algunos atributos y métodos de cada una?
2.	¿Qué relaciones existirían entre esas clases (asociación, herencia, composición, agregación, etc.)?
3.	Menciona al menos cuatro casos de uso para este sistema e indica quién sería el actor principal en cada uno.
En un diagrama de clases incluiría el usuario, con id, nombre, telefono y metodos para solicitar prestamo y devolver libro. el libro con isbn, título, año y métodos para prestar y si está disponible. en categoría con nombre y descripción así mismo el bibliotecario con id, nombre y metodos para registrar prestamo y registrar devolucion. 
Las relaciones serian de asociacion como usuario y libro de mucho a muchos por los prestamos que un usuario puede realizar, categoría y libro de agregación porque una categoría tiene varios libros pero existen de forma independiente y asociación entre un bibliotecario y el préstamo y una clase prestamo que actúa como asociación con atributos. Los cuatro casos de uso serían "solicitar préstamo siendo el actor el usuario" registrar préstamo, siendo el bibliotecario el actor y gestionar catálogo de libros siendo el bibliotecario el actor para añadir o eliminar ejemplares.
Muy buena respuesta. De las tres preguntas, esta es la más sólida hasta ahora.
Lo que estuvo correcto:
•	Identificaste las clases principales: Usuario, Libro, Categoría y Bibliotecario. Además, agregaste la clase Préstamo, lo cual es una decisión de modelado muy acertada porque permite representar la relación entre usuarios y libros con información adicional (fecha, devolución, estado, etc.).
•	Los atributos elegidos son coherentes y los métodos representan bien las responsabilidades de cada clase.
•	Identificaste correctamente la relación de muchos a muchos entre Usuario y Libro, y además propusiste resolverla mediante una clase Préstamo, que es precisamente una práctica común en el diseño orientado a objetos.
•	La relación de agregación entre Categoría y Libro está bien justificada: una categoría puede existir aunque un libro sea eliminado y viceversa.
•	Los casos de uso que propusiste son coherentes con el dominio.
Lo que estuvo incompleto o puede mejorar:
•	Mencionaste tres casos de uso en lugar de cuatro. Propusiste:
1.	Solicitar préstamo.
2.	Registrar préstamo.
3.	Gestionar catálogo de libros.
Faltó uno más, por ejemplo:
o	Registrar devolución.
o	Consultar disponibilidad de un libro.
o	Buscar libros por categoría.
o	Renovar préstamo.
•	Habría sido útil mencionar explícitamente la relación entre Bibliotecario y Préstamo (asociación) y entre Préstamo y Libro (asociación), ya que la clase Préstamo se convierte en el centro de esa interacción.
•	En un diagrama UML de clases también suele indicarse la multiplicidad (1..*, 0..1, etc.). No era obligatorio, pero habría enriquecido la respuesta.
Evaluación de esta pregunta: 9.5/10
Hasta este punto veo un patrón interesante:
•	Tienes facilidad para analizar un problema y transformarlo en objetos y relaciones.
•	Piensas en términos del dominio del negocio antes que en el código, lo cual es una habilidad importante en Ingeniería de Software.
•	Lo que más te resta puntos no son errores conceptuales graves, sino pequeños detalles o conceptos que dejas sin mencionar.
Vamos con la siguiente.
Pregunta 4: Diseño de software
Imagina que estás desarrollando un sistema de ventas para una tienda y otro desarrollador propone escribir todo el código en una sola clase llamada Sistema, donde estarán las funciones para registrar clientes, vender productos, generar facturas, calcular impuestos y administrar inventario.
Pregunta:
1.	¿Qué problemas tendría este diseño?
2.	¿Qué principios o buenas prácticas de diseño aplicarías para mejorarlo?
3.	¿Cómo organizarías las clases de ese sistema? Explica tu razonamiento.
Este diseño tendría problemas porque en sí un sistema tiene que ser escalable si no el sistema terminaría teniendo fallas. Una sola clase no puede albergar funciones específicas para registrar clientes, vender productos, generar facturas o calcular impuestos incluso administrar inventario porque cada uno de ellos tienen tanto código, funcionalidad y procesos que en una clase utilizando ciertos parámetros puede que termine rompiéndose un patrón de buenas prácticas para que funcione. Las buenas prácticas son dividir todas las tareas en áreas independientes, uno que solo maneje clientes otro que controle el inventario, otro donde se hagan facturas o se calculen impuestos. Organizaría el sistema por carpetas o clases diferentes que tengan su código específico para la realización de cada tarea, cada uno relacionado a su función específica
Muy buena respuesta. Se nota que tienes intuición sobre diseño de software, aunque todavía te falta ponerle nombre a algunos principios formales que probablemente verás en IS2.
Lo que estuvo correcto:
•	Identificaste correctamente el problema principal: una única clase concentrando toda la lógica del sistema genera un diseño difícil de mantener y escalar.
•	Explicaste que cada módulo tiene responsabilidades y procesos diferentes, por lo que conviene separarlos.
•	Propusiste dividir el sistema en componentes especializados (clientes, inventario, facturación, impuestos), que es justamente el enfoque recomendado.
•	Tu razonamiento está orientado a la modularidad y al mantenimiento futuro, dos objetivos fundamentales del diseño de software.
Lo que estuvo incompleto o podría mejorar:
•	Habría sido muy valioso mencionar el Principio de Responsabilidad Única (SRP) de SOLID. Es el concepto que describe exactamente el problema que planteaba la pregunta: una clase debería tener una sola razón para cambiar.
•	También podrías haber mencionado otros principios como:
o	Alta cohesión: cada clase realiza una tarea bien definida.
o	Bajo acoplamiento: las clases dependen lo menos posible entre sí.
o	Abierto/Cerrado (OCP): facilitar la extensión sin modificar código existente.
•	En la organización de clases, podrías haber propuesto algo como:
o	Cliente
o	Producto
o	Inventario
o	Factura
o	Venta
o	CalculadoraImpuestos
o	RepositorioClientes o ServicioVentas (si aplicas una arquitectura por capas).
Eso habría demostrado un nivel de abstracción más cercano al diseño profesional.
Evaluación de esta pregunta: 9/10
Hasta ahora observo que entiendes bastante bien qué debe hacerse en un buen diseño. El siguiente paso será aprender a expresar esas ideas utilizando principios de ingeniería (SOLID, GRASP, patrones de diseño, arquitectura por capas, etc.).
Pasemos a la última pregunta.
Pregunta 5: Proceso de desarrollo y metodologías
Una empresa debe desarrollar una aplicación móvil para una startup. El cliente cambia frecuentemente de opinión y suele solicitar nuevas funciones cada dos semanas.
Pregunta:
1.	¿Elegirías una metodología tradicional (como Cascada) o una metodología ágil (como Scrum)? ¿Por qué?
2.	Explica las diferencias principales entre ambos enfoques.
3.	Menciona al menos tres roles o artefactos importantes de Scrum y explica brevemente para qué sirven.
Elegiría una metodología ágil, porque el método SCRUM permite mejor flexibilidad para la realización de tareas. Con cascada se realiza paso por paso y cualquier cambio a mitad de camino es costoso y también lento porque retrocede todo avance. En scrum se entregan versiones que funciones cada pocas semanas para corregir todo error antes de que se acumulen. Una diferencia con cascada es que es secuencial y rígida, no permite cambio a diferencia de scrum que se adapta a los cambios. Tres artefactos importantes de scrum es el product backlog que es una lista priorizada de todo lo que requiere el sistema, el sprint backlog que son todas las tareas que el equipo se compromete a terminar en un sprint detallando cómo se va a hacer y el incremento es la versión del software que queda funcionando al final de cada sprint.
Excelente. Con esta última respuesta ya tengo un panorama bastante claro de tu nivel.
La respuesta estuvo bien fundamentada:
•	Elegiste correctamente una metodología ágil para un proyecto con requisitos cambiantes y justificaste la decisión.
•	Explicaste correctamente la principal diferencia entre Cascada y Scrum: predictibilidad frente a adaptabilidad.
•	Describiste correctamente los tres artefactos de Scrum:
o	Product Backlog
o	Sprint Backlog
o	Incremento
Lo que estuvo incompleto:
•	La pregunta pedía "roles o artefactos". Elegiste tres artefactos, lo cual es válido, pero habría enriquecido la respuesta mencionar alguno de los tres roles:
o	Product Owner: prioriza el Product Backlog y representa al cliente.
o	Scrum Master: facilita el proceso Scrum y elimina impedimentos.
o	Developers (Equipo de Desarrollo): construyen el incremento del producto.
•	También podrías haber mencionado eventos importantes como Sprint Planning, Daily Scrum, Sprint Review o Sprint Retrospective.
Evaluación de esta pregunta: 9.5/10
________________________________________
Evaluación general
Resultado global: 8.9/10 (Nivel: Bueno, cercano a avanzado para IS1)
Diría que estás llegando a IS2 con una base bastante sólida. No das respuestas memorizadas; razonas los conceptos y los aplicas a ejemplos, que es justamente lo que suele distinguir a un estudiante que entiende la materia.
Tu principal área de mejora no es la comprensión, sino la precisión técnica. Muchas veces sabes la idea, pero no utilizas el término formal que un profesor esperaría.
________________________________________
Evaluación por tema
Tema	Calificación
Ciclo de vida del software	8.5/10
Requerimientos	8.0/10
UML	9.5/10
Diseño de software	9.0/10
Metodologías de desarrollo	9.5/10
________________________________________
Lo que estuvo correcto
•	Comprendes el propósito de cada fase del ciclo de vida del software.
•	Sabes identificar funcionalidades del sistema y proponer soluciones.
•	Modelas bien problemas mediante clases y relaciones UML.
•	Tienes buen criterio para modular un sistema.
•	Entiendes cuándo utilizar metodologías ágiles y por qué.
•	Tus ejemplos siempre estuvieron contextualizados al problema.
________________________________________
Lo que estuvo incompleto
Observé un patrón repetido:
1.	En varias respuestas omitiste algunos detalles que la pregunta pedía explícitamente (por ejemplo, las consecuencias de omitir las pruebas o el cuarto caso de uso).
2.	Confundiste un requerimiento de usabilidad ("la plataforma sea intuitiva") con un requerimiento funcional.
3.	Explicas correctamente las ideas, pero rara vez mencionas los nombres formales de los principios o conceptos (SRP, cohesión, acoplamiento, SOLID, etc.).
________________________________________
Tus 3 principales fortalezas
1. Pensamiento analítico
No respondes con definiciones aisladas. Analizas el problema antes de responder y lo conectas con un caso real.
2. Modelado orientado a objetos
Fue el punto más fuerte de la evaluación. Identificaste clases relevantes, relaciones y la necesidad de una clase asociativa (Préstamo) sin que se te sugiriera.
3. Visión de ingeniería
Cuando hablas de diseño, piensas en mantenimiento, escalabilidad y organización del código, no solo en "hacer que funcione". Esa perspectiva es muy valiosa en IS2.
________________________________________
Plan de 3 acciones concretas antes de tu próxima clase
1. Repasa los principios SOLID y los conceptos de cohesión y acoplamiento
Dedica entre 60 y 90 minutos a estudiar:
•	Responsabilidad Única (SRP)
•	Abierto/Cerrado (OCP)
•	Inversión de Dependencias (DIP)
•	Alta cohesión
•	Bajo acoplamiento
En IS2 aparecerán con frecuencia cuando se hable de arquitectura y diseño.
________________________________________
2. Practica clasificando requerimientos
Toma tres sistemas distintos (por ejemplo: banco, hospital y tienda virtual) y escribe para cada uno:
•	10 requerimientos funcionales.
•	10 requerimientos no funcionales.
Después verifica que ninguno de los funcionales describa atributos de calidad (seguridad, rendimiento, usabilidad, disponibilidad, etc.).
________________________________________
3. Diseña sistemas completos en UML
Escoge dos sistemas cotidianos (por ejemplo, un restaurante y un gimnasio) y realiza:
•	Diagrama de casos de uso.
•	Diagrama de clases.
•	Relaciones con multiplicidades.
•	Atributos y métodos principales.
Este ejercicio reforzará tanto UML como el diseño orientado a objetos.
________________________________________
Diagnóstico final
Si tuviera que ubicarte en una escala para iniciar Ingeniería de Software II, diría lo siguiente:
•	Comprensión conceptual: 9/10
•	Aplicación práctica: 9/10
•	Terminología técnica: 7.5/10
•	Capacidad de análisis: 9.5/10
Veredicto: Estás preparado para comenzar IS2. Si dedicas unas horas a reforzar la terminología formal y los principios de diseño, llegarás con una base muy competitiva para abordar temas como patrones de diseño, arquitectura de software, pruebas, calidad y desarrollo ágil avanzado.
