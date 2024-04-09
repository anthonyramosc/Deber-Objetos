#Ejercicios de exercism

1. Hello world!
   En TypeScript, este código define una función llamada hello que no toma ningún argumento y devuelve una cadena de texto. La palabra clave export se utiliza para exportar la función para que pueda ser utilizada en otros archivos TypeScript.

Además, TypeScript es un superconjunto tipado de JavaScript que se compila a JavaScript. Esto significa que el código TypeScript se compila a JavaScript para su ejecución en el navegador o en un entorno de Node.js.

Si deseas ejecutar este código en un navegador, primero tendrías que compilarlo a JavaScript utilizando el compilador de TypeScript. Luego, podrías incluir el archivo JavaScript resultante en una página HTML para ejecutar la función hello.

2. Funcion One for you

En este código, la función twoFer utiliza una asignación por defecto para el parámetro name, lo que significa que si no se proporciona ningún nombre al llamar a la función, se utilizará el valor por defecto "you". Luego, la función devuelve una cadena de texto que incluye el nombre proporcionado (o el valor por defecto) en el formato especificado.

Este tipo de asignación por defecto es una característica de TypeScript que permite proporcionar valores predeterminados para los parámetros de una función en caso de que no se proporcionen al llamar a la función

3. Color Resistor

export const colorCode = (color: string) => {
return COLORS.indexOf(color.toLowerCase());
};

export const COLORS = [
"black",
"brown",
"red",
"orange",
"yellow",
"green",
"blue",
"violet",
"grey",
"white",
];

La función colorCode toma un parámetro color de tipo string y utiliza el método indexOf para buscar el índice de ese color en la matriz COLORS. La función indexOf devuelve el primer índice en el que se encuentra un elemento dado en la matriz, o -1 si no se encuentra. En este caso, se convierte el color proporcionado a minúsculas antes de buscarlo en la matriz para asegurar que la búsqueda sea insensible a mayúsculas y minúsculas.

La matriz COLORS contiene una lista de colores predefinidos. Cada color está representado como una cadena de texto.

Al exportar tanto la función colorCode como la matriz COLORS, se hace posible utilizarlas en otros archivos TypeScript mediante la importación.
