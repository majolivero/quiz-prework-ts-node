# quiz-prework-ts-node

1. JavaScript Básico:

Describe qué es una función en JavaScript y cómo se declara.
Una función es una porción de código encargada de ejecutar una única tarea.
Se declara de la siguiente forma:
function(){

}

2. Manipulación del DOM:

Explica cómo seleccionar un elemento del DOM y cambiar su contenido.

Podemos manipular el DOM con algunos de los siguientes métodos:

document.getElementById(); => Para traer un elemento usando el id
document.querySelector(); => Para traer un elemento usando su id o su clase 
document.byTagName(); 
document.byClassName(); => Para taer un elemento usando su clase 

3. Programación Orientada a Objetos (OOP):

¿Qué es una clase en JavaScript y cómo se define una?

4. Eventos en JavaScript:

¿Cómo se agrega un evento de clic a un botón en JavaScript?

De la siguiente forma: 
*Manipulación del DOM:
botonManipular = document.getElementById(#button);
*Agregar el evento:
botonManipular.addEventListener(e => {

});

5. Variables y Tipos de Datos:

Explica las diferencias entre var, let, y const en JavaScript.

const = Se usa para declarar constantes y arrays.
La diferencia entre var y let es el alcance o scope que permite cada una. 

6. Control de Flujo:

¿Qué son las estructuras de control de flujo y cuáles son algunas de las más comunes en JavaScript?

Las estructuras de control de flujo hacen referencia a las estructuras conocidas como condicionales y ciclos.
Como condicionales tenemos al condicinal if, y a la estructura switch.
Como ciclos tenemos for, forEach, forOf, while.

7. Funciones de Flecha: 
Describe qué es una función de flecha en JavaScript y proporciona un ejemplo de cómo se usa.

Una función flecha es una forma simplificada de expresar funciones.

nombreFuncion() => {

}

8. JSON:

¿Qué es JSON y cómo se utiliza en JavaScript?

JSON significa JavaScript Object Notation, se usa cuando se envían datos desde un servidor a una página web. 

9. Promesas:

Explica qué es una promesa en JavaScript y proporciona un ejemplo de su uso.

10. Depuración:

¿Cuáles son algunas de las herramientas o métodos que se pueden usar para depurar código JavaScript?

Se puede depurar desde el navegador mediante el uso de breakpoints. 


PREGUNTAS DE SELECCIÓN MÚLTIPLE (20)
¿Cuál de las siguientes es la forma correcta de declarar una variable en JavaScript?
A) var myVariable;
B) variable myVariable;
C) let myVariable;
D) A y C son correctas. Opción Correcta.

¿Qué método se utiliza para agregar un elemento al final de un array en JavaScript?
A) push() Correcta
B) pop() 
C) shift()
D) unshift()

¿Cuál de los siguientes operadores se utiliza para comparar tanto el valor como el tipo de dos variables en JavaScript?
A) ==
B) === Correcta
C) !=
D) !==

¿Cuál es la salida del siguiente código?
console.log(typeof null);
A) null   Correcta
B) undefined
C) object
D) number

¿Cuál de los siguientes métodos se usa para recorrer todos los elementos de un array?
A) forEach()
B) map()
C) filter()
D) Todas las anteriores Correcta

¿Qué se entiende por “hoisting” en JavaScript?
A) Declaraciones de variables y funciones se mueven al principio de su ámbito. Correcta
B) Es un término para describir la eliminación de variables.
C) Es un método para agrupar varias funciones.
D) Ninguna de las anteriores.

¿Cuál es la diferencia entre null y undefined en JavaScript?
A) null significa que una variable ha sido declarada pero no definida, undefined significa que no se ha declarado. 
B) null es un valor asignado intencionalmente, undefined significa que una variable no tiene valor. Correcta
C) undefined es un valor asignado intencionalmente, null significa que una variable no tiene valor.
D) No hay diferencia.

¿Cuál es el propósito del método Array.prototype.map()?
A) Modificar el array original.
B) Crear un nuevo array con los resultados de aplicar una función a cada elemento del array original. Correcta
C) Filtrar los elementos de un array.
D) Encontrar un elemento en un array.

¿Qué es el Event Loop en JavaScript?
A) Un ciclo que controla las llamadas recursivas.
B) Un proceso que permite a JavaScript realizar operaciones asincrónicas.
C) Un método para iterar sobre arrays. Correcta
D) Ninguna de las anteriores.

¿Cuál es la salida del siguiente código?
console.log(0.1 + 0.2 === 0.3);
A) true
B) false Correcta
C) undefined  
D) NaN

¿Qué se entiende por strict mode en JavaScript?

A) Un modo que permite utilizar características experimentales.
B) Un modo que cambia la forma en que se ejecuta JavaScript, haciéndolo más seguro.
C) Un método para validar datos.
D) Ninguna de las anteriores. Correcta

¿Cuál de las siguientes es una forma correcta de crear un objeto en JavaScript?

A) let obj = {};
B) let obj = Object.create();
C) let obj = new Object();
D) A y C son correctas. Correcta

¿Qué es un callback en JavaScript?

A) Una función que se pasa como argumento a otra función. Correcta
B) Un tipo de variable especial.
C) Un método para declarar funciones.
D) Ninguna de las anteriores.

¿Cuál es el propósito de async y await en JavaScript?

A) Ejecutar funciones síncronas.
B) Manejar operaciones asincrónicas de manera más simple y legible. Correcta
C) Declarar variables globales.
D) Ninguna de las anteriores.

¿Cuál de las siguientes es una estructura de datos inmutable en JavaScript?

A) Arrays
B) Strings Correcta
C) Objetos
D) Ninguna de las anteriores.

¿Cómo se puede convertir un objeto JSON en una cadena de texto en JavaScript?

A) JSON.parse()
B) JSON.stringify() Correcta
C) toString()
D) parseInt()

¿Qué es un Promise en JavaScript?

A) Una función que se ejecuta inmediatamente.
B) Un objeto que representa la eventual finalización (o falla) de una operación asincrónica.
C) Un método para declarar variables.
D) Ninguna de las anteriores. Correcta

¿Qué método se utiliza para agregar uno o más elementos al principio de un array y devolver la nueva longitud del array?

A) push()
B) pop()
C) shift()
D) unshift() Correcta

¿Cuál es la diferencia entre localStorage y sessionStorage en JavaScript?

A) localStorage almacena datos solo durante la sesión del navegador, sessionStorage almacena datos de manera persistente.
B) sessionStorage almacena datos solo durante la sesión del navegador, localStorage almacena datos de manera persistente. Correcta
C) No hay diferencia entre ellos.
D) Ambos almacenan datos solo durante la sesión del navegador.

¿Qué método se utiliza para detener la propagación de un evento en el DOM?

A) event.stopPropagation() Correcta
B) event.preventDefault() 
C) event.stop()
D) event.cancel()
