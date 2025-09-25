# Proyecto

## Diseño y desarrollo de una estación automatizada para la colocación de imanes en rotores de motores eléctricos

**Aristarco Cortés

# Planteamiento del problema

El ensamblaje de rotores con imanes permanentes en motores eléctricos es una tarea crítica que requiere alta precisión y eficiencia. En la planta de Schaeffler México S. de R.L. de C.V., este proceso se realiza manualmente, lo que implica tiempos prolongados, altos niveles de esfuerzo físico por parte de los operadores y un mayor riesgo de errores humanos. 
 
Este proyecto tiene como objetivo principal desarrollar una estación de trabajo automatizada que optimice el ensamblaje de los imanes, asegurando la calidad y reduciendo el tiempo de operación. El enfoque principal es integrar tecnologías avanzadas para alcanzar mayores niveles de eficiencia y confiabilidad, alineándose con los estándares de la Industria 4.0. 
 
Aquí se presenta el desarrollo integral del proyecto, desde la identificación de la problemática y los objetivos hasta los resultados obtenidos y las conclusiones derivadas del análisis.

# Pregunta:

 *¿Cómo se puede diseñar, implementar y evaluar una estación de trabajo robotizada para el ensamblaje de imanes en rotores de motores eléctricos, optimizando la precisión de la colocación, minimizando los tiempos de ciclo y cuantificando la reducción en el riesgo de errores humanos, en comparación con el proceso de ensamblaje manual?*


**Aspectos clave del problema:**

•	**Diseñar, implementar y evaluar:** Esto establece el marco de un estudio ingenieril completo, que va desde la concepción teórica hasta la verificación práctica del sistema.
•	**Estación de trabajo robotizada:** Especifica la tecnología central que se investigará, que es un sistema automatizado.
•	**Optimización de la precisión de la colocación:** Aborda la calidad del producto final, que es fundamental para el rendimiento del motor.
•	**Minimización de los tiempos de ciclo:** Se enfoca en la eficiencia operativa, un objetivo principal del proyecto.
•	**Cuantificación de la reducción en el riesgo de errores humanos:** Introduce una variable de seguridad y confiabilidad, que es un beneficio significativo de la automatización.
•	**En comparación con el proceso de ensamblaje manual:** Proporciona un punto de referencia claro para validar el éxito y las mejoras del nuevo sistema.

**Objetivos específicos.**

1.	Diseñar y fabricar una plantilla funcional y ergonómica. 
2.	Implementar un sistema de alimentación automática de imanes. 
3.	Diseñar un cabezal colocador de imanes con alta precisión. 
4.	Programar el PLC para coordinar todos los sistemas de manera eficiente. 
5.	Validar el funcionamiento mediante pruebas exhaustivas. 


# Introducción 



# Justificación

    Dado que el motor eléctrico utiliza imanes permanentes, el rotor debe generar varios campos magnéticos que interactúen con el estator y sus devanados. Estos campos se forman gracias a la distribución precisa de diferentes imanes a lo largo del rotor, los cuales están organizados en tres capas, cada una compuesta por 32 imanes. El proceso tradicional requiere que un operador coloque manualmente los imanes en cada capa, para luego apilarlas con un desfase angular entre ellas. 

    Este proceso no solo demanda alta precisión y velocidad debido al tamaño reducido de los imanes, sino que también implica la manipulación de 96 imanes por rotor. Una vez ensamblado, el estator completo es fijado mediante una resina que posteriormente se hornea. En caso de errores durante la colocación, el retiro de la resina resulta sumamente complicado, lo que genera grandes pérdidas de materia prima y tiempo. 

    Actualmente, Schaeffler de México, S. de R.L. de C.V., cuenta con un prototipo de plantilla que facilita el llenado rápido de cada capa. Además, se utiliza una cámara para verificar manualmente que todos los espacios en la plantilla estén ocupados por imanes, reduciendo parcialmente los errores, pero con una dependencia significativa de la intervención humana.




