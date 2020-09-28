# Homework: Javascript V

## Instrucciones
---
1. En un archivo de texto separado que debes crear, escribe explicaciones de los siguientes conceptos como si se lo estuvieras explicando a un niño de 12 años. Hacer esto te ayudará a descubrir rápidamente cualquier agujero en tu comprensión.

* `prototype`: Los prototipos son un mecanismo mediante el cual los objetos en JavaScript heredan características entre sí.
Los objetos pueden tener un objeto prototipo, el cual actúa como un objeto plantilla que hereda métodos y propiedades.

Un objeto prototipo del objeto puede tener a su vez otro objeto prototipo, el cual hereda métodos y propiedades, y así sucesivamente. Esto es conocido con frecuencia como la cadena de prototipos, y explica por qué objetos diferentes pueden tener disponibles propiedades y métodos definidos en otros objetos.
Los métodos y propiedades son definidos en la propiedad prototype, que reside en la función constructora del objeto, no en la instancia misma del objeto.
Las clases tienen una forma única de establecer un método una vez y dar acceso a cada objeto de esa clase a esos métodos. Esto se llama el prototype. Cada clase tiene una propiedad prototype, que luego podemos establecer en métodos.

* _Constructors_ (de Clases): El método constructor es un metodo especial para crear e inicializar un objeto creado a partir de una clase. Cuando creamos un objeto, estamos creando una plantilla. En lugar de copiar esa plantilla una y otra vez, Javascript nos da acceso a lo que llamamos un constructor o class. 
Las clases son útiles para crear muchos objetos que comparten alguna de las mismas propiedades o métodos. 

2. Desde la carpeta `Prep` en la carpeta donde clonaste el repo, ingresa el comando `npm test JSV.test.js` para correr los tests automatizados. Al principio, todos los tests estarán fallados/rotos. Encontrarás las funciones para hacer pasar los tests en el archivo `homework.js`.

### Aca tendras acceso a las [Soluciones](https://github.com/atralice/Curso.Prep.Henry/blob/solution/06-JS-V/homework/homework.js)