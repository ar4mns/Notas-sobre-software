#Review "The Cathedral and the Bazaar"

## La catedral y el bazar

- *El estilo catedral vs el estilo bazar*: El estilo de desarrollo centralizado de personas con gran capacidad que cuidan todos los detalles vs un estilo descentralizado donde cualquier persona puede aportar su grano de arena al desarrollo. Algunas ídeas que chocaban contra el modelo

- *Con los suficientes ojos, todos los errores son fáciles de encontrar*: denominada la "Ley de Linus"

## El correo tenía que llegar

1. **Todos los trabajos buenos en software comienzan tratando de paliar un
problema personal del que los programa**: la necesidad es la madre de todos los inventos

2. **Los buenos programadores saben qué escribir. Los mejores, que reescribir (y reutilizar)**: el hecho de que haya tanta gente compartiendo en las comunidades de Linux y haciendo lo que le gusta, hace que haya más diversidad y una vasta batería de ejemplos desde los que comenzar a *reutilizar*

3. **Planea desechar alguna de las bases, de todas formas tendrás que hacerlo**: dicho de otra forma si tienes un problema que solucionar, plantéate resolverlo al menos una vez.

4. **Si tienes la actitud adecuada, encontrarás problemas interesantes**

5. **Cuando se pierde el interés en un programa, el último deber es delegarlo a un sucesor compentente**

## La importancia de contar con usuarios

- *Tener usuarios es maravilloso*: no solo porque prueban que están satisfacciendo una necesidad sino porque pueden convertirse en magníficos asistentes.

6. **Tratar a los usuarios como "co-desarrolladores" es la ruta más apropiada para mejorar el código, y la más efectiva de depurarlo**

7. *La genialidad de Linus no fué la de la invención del kernel, sino la de la invención del modelo de desarrollo de Linux*: too lazy to fail.

## Libere temprano y a menudo

8. **Libere temprano y a menudo y escuche a sus clientes**: esto no era un concepto que introdujera el modelo bazar de Linux, pero si que lo llevo a un nivel de intensidad que estaba acorde con la complejidad de lo que se estaba desarrollando. 

*¿Cómo lo hace?*: porque mantiene el interés de sus usuarios/hackers/asistentes constantemente estimulados y recompensados por tomar parte en la acción y por permitir satisfaccer su ego, que premia la exhibición y mejora constante, casi diaria, de su trabajo.

9. **Dada una base suficiente de desarrolladores, beta-testers, casi cualquier problema puede ser caracterizado rápidamente y su solución ser obvia al menos para alguien**: el modelo catedral en este caso tiene un cuello de botella al ser un grupo de personas menor que necesitan más tiempo para realizar un trabajo similar y sin una recompensa frecuente.

- Se menciona el efecto Delphi: *la opinión promedio de un número grande de observadores que son expertos (o ignorantes) en un tema es más confiable que la de una persona observadora experta (o ignorante) elegida al azar*. Aplicable también a la depuración de un proyecto 

- *Una mayor cantidad de usuarios detecta más errores debido a que se dispone de diferentes maneras de evaluar un programa*: 

## Cuantos ojos controlan la complejidad

- El problema fundamental de desarollo de software tradicional alcanza la Ley de Brooks: *"añadir más programadores a un proyecto en desarrollo lo retrasa"*. De manera genera, lo que predica la ley de Brooks es que la complejidad y los costes de comunicación se elevan al cuadrado con el número de desarolladores, mientras que el trabajo hecho tiene una evolución lineal. Ésta ley de Brook se apoya en la suposición de que la estructura de comunicación de un proyecto debe ser necesaria mente un grafo completo (KK).

## ¿Cúando una rosa no es una rosa?

1. **Las estructuras de datos inteligentes y el código burdo funcionan mucho mejor que en el caso inverso**: de una forma u otra se puede extrapolar a un modelado de datos adecuado frente a una lógica de negocio floja.

1. **Si usted trata a sus analistas (beta-testers) como si fueran su recurso más valioso, ellos le responderán convirtiéndose en su recurso más valioso**.

## Popclient se convierte en FetchMail

1. **Lo más grande, después de tener buenas ideas, es reconocer las buenas ideas de sus usuarios. Esto último es a veces lo mejor**

1. **Frecuentemente, las soluciones más innovadoras y espectaculares provienen de comprender que la concepción del problema era errónea**

1. **"La perfección (en diseño) se alcanza no cuando ya no hay nada que agregar, sino cuando ya no hay algo que quitar."**

## El crecimiento de Fetchmail

1. **Toda herramienta es útil empleándose de la forma prevista, pero una *gran* herramienta es la que se presta a ser utilizada de la manera menos esperada**

1. **Cuándo se escribe software para una puerta de enlace de cualquier tipo, hay que tomar la precaución de alterar el flujo de datos lo menos posible, y ¡*nunca* eliminar información a menos que los receptores obliguen a hacerlo!**

## Algunas lecciones extraídas de Fetchmail

1. **Cuando su lenguaje está lejos de un Turing completo, entonces el azúcar sintáctico puede ser su amigo**

- *escuela de diseño "hágalo un lenguaje"*: introducir una sintáxis que permita la legibilidad del diseño de software. La utilización de lenguajes de control que permitían economizar recursos de cómputo vs un lenguaje legible como el inglés con una redundancia de 50%. Ahora es más importante para un lenguaje el ser conveniente para los humanos que ser económico en términos de recursos computacionales.

1. **Un sistema de seguridad es tan seguro como secreto. Cuídese de los secretos a medias**

## Condiciones necesarias para el Estilo del Bazar

- *No se puede partir de 0 para construir software siguiendo el modelo Bazaar*

- *originalidad --> elegancia y complejidad, inteligencia --> simpleza y robustez*: es necesario la suma adecuada de todos para que en el diseño de software se obtenga un programa estable y reconocido

- *un coordinador o lider de proyecto debe tener don de gentes y buena capacidad de comunicación*

- *Formación de una comunidad*: se necesita atraer gente, interesada en lo que se está haciendo y mantenerla a gusto. El entusiasmo técnico es importante, pero más lo es la personalidad que se proyecta en la misma.

- *Es necesaria un poco de capacidad para las relaciones sociales*

## El contexto social del software libre

1. **Para resolver un problema interesante, comience por encontrar un problema que le resulte interesante**

- *La "función utilidad" que los hackers de Linux están explotando no es económica en el sentido clásico, sino algo intangible como la satisfacción de su ego y su reputación entre otros hackers.*

1. **Si el coordinador de desarrollo tiene un medio al menos tan bueno como lo es Internet, y sabe dirigir sin coerción, muchas cabezas serán, inevitablemente, mejor que una**: una reformulación de la Ley de Brooks asociada al modelo Bazaar. En contraposición directa con lo de que el número de personas retrasa el proyecto.

