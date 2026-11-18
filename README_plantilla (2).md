# Nombre de tu escena

Tu nombre · Realidades Extendidas y Experiencias Inmersivas · UGM · 2026

## 1 · Qué es
la idea es logra generar una herramienta terapeutica donde se aborda los hitos adverso de la historia de vida del usurio.

Al ser una herramienta terapéutica el usuario debe estar en un proceso de intervención psicológica, tampoco es un instancia inicial del proceso terpeutico, sino que ya debe haber una vinculo con el terapeuta quien debe guiar el recorrido por la experiencia.

Ansiedad, frustración, descubrimiento y resignificación, todo de manera gestionable  
Una o dos frases: qué experiencia es, para quién es y qué debería sentir quien entra.

Resignificación

## 2 · Cómo se usa

- Enlace a la escena: https://...
- Dispositivo pensado: computador, eperanado con visor en el futuro aplicable
- Al entrar: en esta punto solo podemos por ahora hablar de supuestos, debido a que aun he podido enlazar las diferentes interacciones unas con otras (de ahí los tres links a revisar), inicialmente el usuario en en la estación de trenes debe acercarse y cliquear el tren para entrar al vagón, la cual es otra interacción donde debe recorrer el vagón y interactuar en tres instancias en este caso identificadas con un cuadrado, un cono y una esfera cada instancia debe llevar a una integración diferente 1 construcción a través del lenguaje, Madre, reconociendo a mi niño interior, dentro de lo que se ha realizado están la instancias de la estación, el vagón y el niño interior    

## 3 · Cómo está hecha

- Herramienta: A-Frame, publicado en GitHub Pages.
- Archivos que usé:
- la intención inicial era utilizar solo activos, debido a lo personalmente consideraba mas difícil de levantar directamente en A-frame los elementos como el vagón y la estación. pero se me presento la dificultad de no poder establecer la etiqueta de asset dentro del código, por diferentes variables por lo que aun no han sido puestos en las interacciones, por lo que se decidí realizar las instancias en A-frame solicitando a la IA que tradujera las imágenes de donde iba a sacar los activos a lenguaje de código para la creación de las interacciones      
loe activos a ocupar son lso siguientes
  - **activos/silla.glb**: modelo 3D. Origen: lo hice yo / sitio web. Licencia: ...
  - **activos/campana.mp3**: sonido al clic. Origen: freesound.org. Licencia: CC0

## 4 · Decisiones

- Qué decidí y por qué (luz, sonido, materiales, interacción).
- Qué cambió respecto de lo que propuse en la Solemne 1, y por qué.

## 5 · Testing

Video del recorrido: https://...

### Abrir el enlace en ventana privada
- Resultado: ...
- Ajuste que hice: ...

### Dispositivo elegido
- Resultado: ...
- Ajuste que hice: ...

### Interacciones, una por una
- Resultado: ...
- Ajuste que hice: ...

### Sonido con audífonos
- Resultado: ...
- Ajuste que hice: ...

### Fluidez del recorrido
- Resultado: ...
- Ajuste que hice: ...

### Entrar como si fuera la primera vez
- Resultado: ...
- Ajuste que hice: ...

## 6 · Uso de IA
 -En una primera etapa, se trabajó con Vizcom para desarrollar conceptualmente las escenas que conforman el proyecto, específicamente la estación, el interior del vagón y la representación del niño interior. Este proceso permitió explorar propuestas visuales, definir la estética de los espacios y establecer una primera aproximación a la composición y ambientación de cada escena.
Posteriormente, debido a las limitaciones de conocimiento técnico en modelado 3D, se utilizó la misma herramienta para generar modelos tridimensionales de los escenarios y elementos principales, entre ellos la estación, el vagón, el niño interior y una mochila, los cuales fueron exportados en formato GLB. Sin embargo, durante las pruebas de implementación no fue posible integrar correctamente estos activos en el entorno de desarrollo. Se realizaron diferentes intentos de incorporación hasta alcanzar el límite de uso mensual de la plataforma, lo que obligó a buscar una alternativa para continuar avanzando.
Frente a esta dificultad, se optó por utilizar las imágenes de referencia generadas en Vizcom y trabajar con ChatGPT como herramienta de asistencia para traducir sus características visuales a código compatible con A-Frame. De esta manera, se construyeron representaciones tridimensionales simplificadas mediante elementos geométricos, materiales, colores y posiciones espaciales. Aunque estas versiones no reproducen completamente la complejidad visual de las propuestas originales, permitieron establecer una estructura funcional sobre la cual desarrollar y probar las interacciones previstas para el proyecto. 

  -A partir del código generado con asistencia de ChatGPT, se desarrolló un proceso de revisión, experimentación y modificación de los diferentes componentes de las escenas. Mi intervención se concentró principalmente en adaptar las propuestas generadas a las necesidades narrativas, visuales e interactivas del proyecto, identificando los parámetros que debían modificarse y evaluando sus resultados mediante pruebas sucesivas. Uno de los principales aspectos trabajados fue la configuración de la cámara, particularmente sus perspectivas, posiciones, movimientos y mecanismos de control. Se realizaron ajustes orientados a conseguir los encuadres y desplazamientos necesarios para la experiencia, buscando compatibilizar la navegación del usuario con la posibilidad de interactuar con los elementos presentes en cada escenario. Asimismo, se identificaron y modificaron componentes específicos de las escenas, ajustando sus colores, dimensiones y posiciones para aproximarlos a las propuestas visuales originales. También se incorporaron elementos interactivos que permitirán establecer vínculos con futuras escenas y acciones dentro del recorrido narrativo. Estas interacciones se implementaron inicialmente de manera funcional y provisoria, considerando su posterior reemplazo o adaptación una vez que sea posible integrar los modelos tridimensionales originales.
Durante este proceso también se experimentó con los ritmos y velocidades de movimiento de la cámara. En algunas escenas fue posible realizar modificaciones que mejoraron la experiencia de navegación, mientras que en otras fue necesario simplificar o sacrificar determinados movimientos para priorizar el funcionamiento de las interacciones. Estas decisiones responden a un proceso de aprendizaje técnico y experimentación, en el que todavía se busca establecer un equilibrio entre la intención audiovisual, la libertad de navegación y las posibilidades de interacción.
En este sentido, mi aporte no se limitó a utilizar los resultados entregados por las herramientas de inteligencia artificial, sino que consistió en definir las características visuales y narrativas, seleccionar y adaptar las soluciones propuestas, modificar parámetros, realizar pruebas, identificar problemas técnicos y tomar decisiones respecto de qué elementos mantener, transformar o descartar.
El resultado hasta esta etapa corresponde a una estructura interactiva preliminar que, si bien todavía requiere mejoras visuales y técnicas, permite avanzar en la construcción de la experiencia y comprender las posibilidades y limitaciones de A-Frame para el desarrollo del proyecto.

## 7 · Pendientes para el examen

- 1 establecer la vinculación de las interacciones a la pagina del vagón y la estación y de las interacciones de vuelta al vagón, lograra insertar los activos y trabajar con los diseños en contexto a la experiencia y establecer los sonidos necesarios, diseñar las interacciones faltantes para completar las experiencias, establecer el limite de movimiento para evitar los desaforos  
