## Explica los siguentes conceptos con tus propias palabras. (no más de tres líneas por respuesta).

* Estructura de Datos: Es una forma en la que almacenar la información para que quede ordenada de la manera que más nos convenga. El ejemplo más básico es un array.

* Lista Enlazada: Es una estructura de datos. Cada uno de los elementos que la componen (llamados nodos) están conectados con el siguiente nodo de la lista, pero no con el anterior.
Es decir, la lista va en una sola dirección.

* Árbol: Es una estructura de datos. Posee un nodo raíz, que tiene otros nodos denominados "hijos", los cuales a su vez también pueden tener nodos hijos. Dentro del mismo árbol puede haber varios sub-árboles.

* Closures: Con las closures podemos hacer referencias a contextos que ya no están porque ya han sido ejecutados y destruidos.

* Contexto de Ejecución: Es una forma que tiene Javascript de mantener cierto "orden" en el código, dividiendolo en partes. Por ejemplo, al definir una función, todo lo que en ella se
haya especificado se ejecutará en otro contexto para evitar errores. Por ejemplo, si definimos una variable dentro de una función, esta solamente funcionará dentro de esa función.

* Variable THIS: Esta variable hace una referencia a un objeto. Si la llamamos dentro de una función, por ejemplo: "this.nombre" hará referencia a la propiedad nombre de un objeto. La referencia que haga dependerá de dónde haya sido llamada la variable This.

* Hoisting: Lo que este concepto aplica es trasladar todas las definiciones de variables a la parte superior del código (no la mueve físicamente, seguirán estando donde estaban). Esto quiere decir que al iniciar el código lo que primero hará será guardar todas las definiciones de variables en memoria, sin importar dónde se encuentren, puesto que las lleva a la parte superior primero.

* Pasar por valor y por referencia: Cuando se pasa una variable por referencia, lo que se hace es crear una referencia a un objeto. Cualquier cambio sobre esa referencia cambiará el objeto original. En cambio, si se pasa por valor, lo que se pasa es el objeto en sí, esto quiere decir que si se hace un cambio en el objeto, se cambiará en ambos, pues son el mismo objeto.

* Algoritmo: Un algoritmo es un conjunto de instrucciones o reglas bien ordenadas y definidas, con el objetivo de realizar una actividad. Estas reglas o instrucciones no deben generar duda alguna en quien lo emplea, es decir, debe ser comprensible para quien necesita del algoritmo para hacer una tarea. Básicamente es una serie de pasos que debemos seguir para concretar una tarea específica.

* Big O notation: 

* Inmediatly Invoked Function Expression (IIFF): Lo que se hace básicamente aquí es invocar directamente la función luego de ser definida. Al llegar a la línea de código donde invocamos la función, creará un nuevo contexto de ejecución, lo que quiere decir que lo que ocurra en ese trozo de código se quedará ahí dentro, sin ocasionar problemas en el resto, por lo que sirve bastante cuando se trabaja con varias personas en un mismo archivo, para no colisionar con otras variables, por ejemplo.
