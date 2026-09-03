# Prompts de vídeo amb timeline

Utilitza aquesta referència quan calgui animar una imatge, generar un vídeo, conservar un personatge o continuar un clip.

## Criteris pràctics

- El model interpreta el prompt aproximadament segons l'ordre temporal del vídeo.
- Utilitza un màxim de tres intervals per a clips curts.
- Assigna una única acció dominant a cada interval.
- Protegeix primer la identitat i la composició; després descriu el moviment.
- No tornis a descriure tota la imatge: indica només què es mou i què no pot canviar.
- Utilitza un únic moviment de càmera motivat.
- Especifica sons concrets. Si no hi ha veu, prohibeix el diàleg i el moviment de llavis.
- Per preservar millor la cara, prefereix accions petites, càmera suau i clips de 6 a 10 segons.

## Plantilla mestra

```text
[CONTINUIDAD ABSOLUTA]

Comenzar exactamente desde la imagen proporcionada. Mantener sin cambios la identidad facial, edad aparente, proporciones corporales, peinado, ropa, accesorios, lateralidad, escenario, iluminación y posición inicial de todos los elementos.

[TIMELINE — DURACIÓN TOTAL: [DURACIÓN] SEGUNDOS]

0–[A] segundos:
[PRIMERA ACCIÓN SENCILLA Y OBSERVABLE].

[A]–[B] segundos:
[ACCIÓN PRINCIPAL]. Mantener anatomía, orientación espacial y continuidad del movimiento.

[B]–[FINAL] segundos:
[ACCIÓN FINAL SENCILLA]. Terminar en una postura estable y natural, adecuada para continuar desde el último fotograma.

[CÁMARA]

La cámara realiza un único movimiento: [MOVIMIENTO]. Movimiento suave, continuo y estable. Mantener al personaje correctamente encuadrado. Sin cortes ni cambios repentinos de perspectiva.

[MOVIMIENTO Y FÍSICA]

Movimiento corporal realista, con peso, equilibrio, contacto correcto con el suelo e inercia natural. Parpadeo ocasional y respiración sutil. El cabello y la ropa reaccionan suavemente al movimiento y al ambiente.

[AUDIO]

Ambiente: [SONIDOS CONCRETOS DEL LUGAR].
Efectos: [PASOS, ROPA, OBJETOS U OTROS SONIDOS].
Diálogo: [NINGUNO O FRASE EXACTA].
Música: [NINGUNA O DESCRIPCIÓN].

[RESTRICCIONES]

Mantener exactamente el mismo rostro, cuerpo, peinado, ropa, accesorios, lateralidad y escenario. No añadir, eliminar, intercambiar ni duplicar personas u objetos. Sin deformaciones anatómicas, manos defectuosas, morphing facial, movimientos robóticos, cámara lenta artificial, parpadeos visuales, cambios de iluminación, texto, subtítulos, logotipos ni marcas de agua.
```

## Continuació d'un vídeo

Descriu primer l'estat exacte de l'últim fotograma i després només l'acció següent. No repeteixis tota la història ni el prompt original.

```text
Continuar directamente desde el último fotograma del vídeo anterior. En el primer fotograma, [ESTADO EXACTO DEL PERSONAJE, OBJETOS, CÁMARA Y ESCENARIO].

[TIMELINE]
0–[A] segundos: [ACCIÓN].
[A]–[FINAL] segundos: [ACCIÓN Y POSICIÓN FINAL].

Mantener exactamente los mismos personajes, rostros, ropa, objetos, iluminación, escenario, dirección de movimiento y estilo de cámara. Transición continua y natural, sin salto, morphing ni reinicio de la acción.
```
