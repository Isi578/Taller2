Pregunta 1:
a. ¿Qué patrón de diseño utilizaría?
R/ Utilizaria el patrón decorator
b. ¿Por qué este patrón es más apropiado que crear una clase diferente para cada combinación?
R/ Porque permite agregar funciones como logging, encriptación y compresión sin modificar la clase original. Además, se pueden combinar las funciones sin tener que crear muchas clases diferentes

Pregunta 2:
a. ¿Qué patrón de diseño utilizaría?
R/ Utilizaria el patrón facada
b. Explique en 2 o 3 líneas por qué considera que este patrón es apropiado.
R/ Porque permite realizar todo el proceso de compra desde una sola clase. Así, el controlador no tiene que llamar a cada servicio por separado ni conocer cómo funciona cada uno

Pregunta 3:
a. ¿Qué patrón de diseño estructural utilizaría?
R/ Utilizaria el patrón proxy
b. Explique brevemente por qué es adecuado para esta situación.
R/ Porque permite revisar si el usuario tiene permiso antes de consultar la información. Así, se protege el acceso sin tener que modificar el servicio original

Pregunta 4:
a. ¿Qué patrón de diseño utilizaría?
R/ Utilizaria el patrón adapter
b. Explique cuál es el problema que debe resolver el patrón.
R/ Permite conectar dos clases que utilizan métodos diferentes. En este caso, adapta el método makeTransaction() del servicio externo al método processPayment() que utiliza la aplicación, sin modificar la clase externa
