# Homework: Javascript IV

## Instrucciones
---
1. En un archivo de texto separado que debes crear, escribe explicaciones de los siguientes conceptos como si se lo estuvieras explicando a un niño de 12 años. Hacer esto te ayudará a descubrir rápidamente cualquier agujero en tu comprensión.

	* Objetos: colección de propiedades o estructura de datos que tienen propiedades que puede ser cualquier tipo de dato de Javascript: strings, numeros, boleanos, matriz, función inlcuso otro objeto.
	* Propiedades: es una asociación entre un nombre o clave y un valor.
	* Métodos: En los objetos, los valores se pueden establecer en funciones. Las funciones guardadas en un objeto se denominan métodos, algunos ejemplos de métodos son .length, .push, .pop etc.
	* Bucle `for…in`: Cuando se quiere iterar (realizar cierta accion varias veces) sobre cada par clave-valor en el objeto. Con las matrices, se utiliza un estándar para el bucle y una variable de número de índice. Los objetos no contienen índices numéricos, por lo que el bucle estándar no funcionará para los objetos. Javascript tiene un segundo tipo de bucle for integrado llamado "for ... in loop". Es una sintaxis ligeramente diferente, comienza igual pero entre paréntesis se declara una variable, la palabra clave in y el nombre del objeto. Esto recorrerá cada clave del objeto y finalizará cuando se hayan iterado todas las claves. Se puede usar esta clave, y la notación de corchetes, en el bucle for para acceder al valor asociado con esa clave.
	* Notación de puntos vs notación de corchetes: Permite acceder a las propiedades y/o funciones de un objeto usando notacion de puntos o corchetes. 
	  Con la notación de puntos podemos llamar al nombre del objeto, un punto y el nombre de la clave. 
	  Cuando usamos corchetes podemos acceder a propiedades que tienen un espacio o carácter no permitido en la notación de punto, aunque con corchetes debemos usar una cadena o número, o una variable que apunte a una cadena o número
