# Proyecto

## Diseño y desarrollo de una estación automatizada para la colocación de imanes en rotores de motores eléctricos

**Aristarco Cortés**

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

La colocación de imanes permanentes de neodimio en el estator de un motor es fundamental en ciertos diseños. Los motores de flujo axial, por ejemplo, tienen el flujo magnético paralelo al eje de rotación y a menudo usan imanes de neodimio en el estator.1
Existen varios métodos para la colocación de imanes en el estator:

1. **Unión con Adhesivos:** Este método, común tanto en rotores como en estatores, utiliza epoxis u otros adhesivos para fijar los imanes.2 Los adhesivos dispersan la tensión en toda la superficie de unión, lo que reduce el riesgo de fractura en los imanes de neodimio, que son frágiles.3 Un desafío clave es la necesidad de un curado a baja temperatura para evitar la desmagnetización de los imanes de neodimio, que tienen una resistencia a la temperatura más baja que otros tipos de imanes.3

2. **Encapsulación:** Esta técnica implica colocar los imanes y el núcleo del estator en un molde y luego inyectar un material resinoso, como compuestos de moldeo de epoxi termoendurecibles (EMC), para rellenar los huecos y asegurar los componentes.2 Este método asegura una unión fuerte entre el imán y el núcleo del estator y proporciona una buena capacidad de relleno.10 La encapsulación ayuda a proteger los imanes y puede mejorar la confiabilidad del motor.4 En algunos casos, los imanes se encapsulan en una "cápsula" de metal o un material conductor, lo que puede afectar el flujo de corriente.4

3. **Fijación Mecánica:** Aunque no se detalla un método específico para el estator en la investigación, la fijación mecánica en general es una técnica para la sujeción de imanes. En los motores de flujo axial, se utilizan a veces imanes en forma de cuña o imanes anulares laminados para reducir el sobrecalentamiento.1 La fabricación aditiva (impresión 3D) también está siendo investigada para crear estructuras de estator complejas con materiales magnéticos, lo que podría incluir la colocación de imanes dentro de la estructura misma.5

4. **Sistemas de Manufactura Automatizada:** Las máquinas automatizadas de inserción y unión pueden manejar la colocación de imanes tanto magnetizados como no magnetizados en el estator.6 Estas máquinas, a menudo equipadas con sistemas robóticos, garantizan un posicionamiento preciso y repetible, lo que es crucial para la calidad del producto.7
La selección del método de colocación depende del diseño específico del motor (p.ej., flujo axial vs. flujo transversal), la topología del estator y los requisitos de rendimiento.


# Justificación

 Dado que el motor eléctrico utiliza imanes permanentes, el rotor debe generar varios campos magnéticos que interactúen con el estator y sus devanados. Estos campos se forman gracias a la distribución precisa de diferentes imanes a lo largo del rotor, los cuales están organizados en tres capas, cada una compuesta por 32 imanes. El proceso tradicional requiere que un operador coloque manualmente los imanes en cada capa, para luego apilarlas con un desfase angular entre ellas. 

Este proceso no solo demanda alta precisión y velocidad debido al tamaño reducido de los imanes, sino que también implica la manipulación de 96 imanes por rotor. Una vez ensamblado, el estator completo es fijado mediante una resina que posteriormente se hornea. En caso de errores durante la colocación, el retiro de la resina resulta sumamente complicado, lo que genera grandes pérdidas de materia prima y tiempo. 

 Actualmente, Schaeffler de México, S. de R.L. de C.V., cuenta con un prototipo de plantilla que facilita el llenado rápido de cada capa. Además, se utiliza una cámara para verificar manualmente que todos los espacios en la plantilla estén ocupados por imanes, reduciendo parcialmente los errores, pero con una dependencia significativa de la intervención humana.


# Bibliografía


1. [Motor de flujo axial - Tengye is a magnet](https://tymagnets.com/es/motor-de-flujo-axial/)
2. [Magnet fixing | EV Propulsion Systems - Caplinq](https://www.caplinq.com/emobility/ev-propulsion-systems/magnet-fixing/) 
3. [E-motor Magnet Bonding - What is the best adhesive for magnet? - PROSTECH](https://prostech.vn/e-motor-magnet-bonding/)
4. [Modelo de capas para motores encapsulados de imán permanente con arranque en línea](https://www.scielo.org.mx/scielo.php?pid=S1405-77432016000100087&script=sci_abstract)
5. [Conventional axial flux machine stator fabrication procedure. - ResearchGate](https://www.researchgate.net/figure/Conventional-axial-flux-machine-stator-fabrication-procedure_fig3_371534351)
6. [Magnet bonding machines, acceso: septiembre 25, 2025](https://rimacmachines.com/en/magnet-bonding-machines/)
7. [Advantages of Automatic Magnet Inserting Equipment - HONEST Automation](https://en.cnhonest.com/news/324.html)






