# Referencias y continuidad entre generaciones

Utiliza esta referencia para preparar imágenes antes de generar, mantener continuidad entre clips y reducir errores, versiones inútiles y consumo innecesario de créditos.

## Preparación y jerarquía de referencias

Antes de escribir el prompt, asigna una función explícita a cada imagen:

- identidad facial;
- cuerpo y proporciones;
- vestuario y calzado;
- marcas corporales;
- escenario y geografía;
- composición o plano;
- estilo visual;
- primer fotograma;
- último fotograma.

Una imagen no controla automáticamente todos los elementos. En el prompt declara qué debe extraerse de cada referencia y qué no debe copiarse.

Comprueba que el rostro sea legible, que el vestuario y los colores puedan identificarse, que las imágenes no estén reflejadas y que no existan contradicciones. Si dos referencias definen de forma diferente el mismo elemento, pregunta cuál tiene prioridad.

## Configuración previa

Antes de preparar una generación confirma o deduce de forma segura:

- herramienta de destino;
- imagen o vídeo;
- relación de aspecto y resolución;
- duración y velocidad narrativa;
- presencia de sonido o diálogo;
- número de personajes;
- referencias disponibles;
- uso de imagen inicial, final o ambas.

Si el usuario no indica formato, utiliza 16:9 horizontal y 1920 × 1080. No inventes una duración de vídeo cuando afecte al diálogo o a la viabilidad de la acción: pregúntala o propón una duración razonada.

## Continuidad entre clips

Registra el final de cada clip y úsalo como estado inicial del siguiente:

- posición y orientación de personajes;
- postura, mirada y emoción;
- mano y agarre de objetos;
- estado de ropa, cabello, heridas y suciedad;
- posición de elementos móviles;
- dirección de cámara y eje de acción;
- iluminación, clima y momento del día;
- diálogo o sonido que continúa.

Cuando sea posible, utiliza el último fotograma aprobado de un clip como referencia inicial del siguiente. No asumas que el generador recordará el plano anterior.

## Primer y último fotograma

Si la herramienta admite referencias inicial y final, comprueba antes que ambas imágenes sean compatibles:

- misma identidad y vestuario;
- misma escena y dirección de luz;
- cambio corporal físicamente posible;
- objetos presentes en ambos extremos o traslado explicado;
- perspectiva y escala que permitan una transición plausible.

Si las imágenes exigen una transformación imposible en la duración disponible, divide la acción en más de un plano.

## Movimiento e interacción física

Describe cada acción mediante sujeto, inicio, trayectoria, contacto y resultado. Mantén peso, equilibrio, inercia y reacción del entorno.

Para caminar o correr, fija dirección, ritmo, contacto de pies y seguimiento de cámara. Para manipular objetos, fija mano, agarre, peso, posición inicial y destino. Para cabello y ropa, describe solo la reacción causada por movimiento, viento o gravedad.

Evita acumular acciones complejas simultáneas. Si existen cruces, multitudes, combate, vehículos o contacto entre cuerpos, prioriza trayectorias separadas y legibles.

## Lateralidad anatómica y verificación de las manos

«Derecha» e «izquierda» se refieren siempre al lado anatómico del personaje, nunca al lado de la imagen ni al punto de vista del espectador. En prompts y revisiones utiliza las expresiones **mano derecha anatómica del personaje** y **mano izquierda anatómica del personaje** cuando exista riesgo de confusión.

Antes de afirmar qué mano realiza una acción:

1. identifica si el personaje está de frente, de espaldas, de perfil o en tres cuartos;
2. localiza el hombro correspondiente;
3. sigue visualmente el brazo completo desde el hombro hasta el codo, la muñeca y la mano;
4. comprueba el agarre o el punto de contacto con el objeto;
5. contrasta el resultado con la referencia aprobada y con el estado del plano anterior.

Reglas de orientación:

- Si el personaje mira de frente, su mano derecha suele aparecer en el lado izquierdo de la imagen y su mano izquierda en el lado derecho.
- Si está de espaldas, su mano derecha suele aparecer en el lado derecho de la imagen y su mano izquierda en el izquierdo.
- En perfil, tres cuartos, reflejos, brazos cruzados, torsiones o encuadres parciales, no deduzcas la mano por su posición en pantalla: sigue la unión anatómica desde el hombro.
- Una imagen reflejada o volteada puede invertir la lectura aparente. Comprueba marcas corporales, cierres, bolsillos, accesorios u otros rasgos asimétricos antes de decidir.

Al redactar una verificación, explica brevemente el razonamiento visual cuando la lateralidad sea importante. Ejemplo: «El teléfono está en la mano derecha anatómica del personaje, situada a la izquierda de la imagen porque está mirando de frente».

Si el hombro, el brazo o la mano están ocultos, cortados, deformados o no se pueden seguir con seguridad, responde **«no se puede verificar con seguridad»** y solicita una vista más clara o una referencia adicional. No conviertas una suposición en una verificación.

Para reducir errores entre generaciones, fija en la biblia de continuidad qué objeto lleva cada mano y repite esa asignación en cada prompt posterior. Cuando sea viable, conserva también un rasgo asimétrico visible —pulsera, reloj, cicatriz o manga— que ayude a reconocer el lado sin rediseñar al personaje.

## Varios personajes

Asigna a cada personaje:

- una referencia de identidad;
- posición inicial;
- acción y trayectoria;
- dirección de mirada;
- diálogo y turno de habla;
- objetos y lateralidad;
- relación espacial con los demás.

Evita descripciones como «ellos hablan y se mueven» cuando las acciones puedan confundirse. Nombra o identifica visualmente a cada sujeto y distribuye las acciones en el tiempo.

## Dividir planos difíciles

Considera dividir el plano cuando contenga varias de estas dificultades:

- más de dos personajes protagonistas;
- diálogo simultáneo;
- cambio complejo de cámara;
- carrera con obstáculos o cruces;
- intercambio de objetos;
- transformación física o de vestuario;
- multitudes, vehículos, agua, fuego o destrucción;
- recorrido largo con cambios de escenario.

Explica brevemente el riesgo y propone la división más sencilla antes de consumir una generación.

## Control de créditos

- No generar una imagen o vídeo si el usuario solo ha pedido un prompt.
- Ante blueprints o fichas técnicas, preguntar si quiere prompt, imagen o ambos.
- Mostrar ejemplos existentes antes de generar cuando ayuden a elegir.
- Revisar el prompt antes de enviarlo al generador.
- No crear todas las variantes posibles: generar solo la seleccionada.
- No reconstruir automáticamente todos los cuadros de un storyboard.
- No repetir una generación para corregir un fallo sin autorización, salvo que el usuario haya autorizado expresamente un proceso iterativo.
- Preferir una edición localizada cuando el resto del resultado ya sea correcto.

## Registro de versiones

Para cada resultado aprobado, conserva cuando el entorno lo permita:

- nombre breve y número de versión;
- herramienta y configuración relevante;
- prompt utilizado;
- referencias y función de cada una;
- formato, resolución y duración;
- decisiones de continuidad;
- errores observados y correcciones aplicadas;
- archivo aprobado que sustituye a versiones anteriores.

No borres versiones anteriores sin permiso. Diferencia claramente borrador, candidato y aprobado.

## Acabado final

Antes del montaje, comprueba:

- coincidencia de color y exposición entre planos;
- estabilidad de cara, manos, ropa y objetos;
- ausencia de parpadeos, deformaciones y elementos que aparecen o desaparecen;
- sincronización de diálogo y labios;
- continuidad de ambiente, efectos y música;
- resolución y relación de aspecto correctas;
- márgenes seguros para recorte, subtítulos o formato final.

No ocultes defectos importantes mediante reescalado, enfoque, grano o corrección de color. Corrige primero la causa cuando sea viable.
