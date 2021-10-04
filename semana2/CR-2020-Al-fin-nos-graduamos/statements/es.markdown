# Descripción

"Al fin nos graduamos" fue la frase célebre que le dijo Sebastián, alias "El fósil", a su amigo Brandon a la hora de meter sus últimas materias en el ITAM. Sebastián, alumno de Computación, está en su último semestre y lo está festejando como si hubiera ganado la copa del mundo. Sus amigos, cansados de Sebastián por presumido, le advirtieron que le echara ganas o reprobaría y se quedaría de fósil un semestre más.

Como Sebastián le anduvo peleando unos pasteles a Andrea, olvidó echarle ganas a sus materias, por lo que entregó pocas tareas y reprobó sus exámenes. Al final del semestre recibió sus calificaciones, pero las recibió en formato de String, por lo que te ha pedido ayuda para saber si pasó el semestre y se va a graduar, o deberá recursar.

Sebastián **pasó el semestre si tiene más del 80% de materias aprobadas**. De lo contrario, está reprobado y tendrá que recursar.

# Entrada

Un String compuesto por **A's** y **R's**, donde A implica **Aprobado** y R implica **Reprobado**.

# Salida

Un solo caracter. Deberás imprimir "G" (sin comillas), de Graduado, si Sebastián obtuvo más del 80% de sus materias aprobadas. Si no obtuvo más del 80% de sus materias aprobadas, deberás imprimir "F" (sin comillas).

# Ejemplos

||input
ARRAAR
||output
F
||description
Del String de entrada se puede deducir que cursó 6 materias. El 80% de sus materias deberían estar aprobadas, pero solo aprobó la mitad, por lo que no pasó el semestre.
||input
ARAAAAAAAAAR
||output
G
||description
Del String de entrada se puede deducir que cursó 12 materias. El 80% de sus materias deberían estar aprobadas, y aprobó aproximadamente 83%, por lo que sí se graduó.
||end

<details><summary>Checa la `plantilla.py`</summary>

{{plantilla.py}}

</details>
