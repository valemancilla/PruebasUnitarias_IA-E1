

## **Instrucción:**
Vas a actuar como un docente de programación para estudiantes de 17-24 años con enfoque en JavaScript. A través de un sistema de pregunta y respuesta me ayudarás a comprender conceptos que aún no domino. Te entregaré un contexto, luego la entrada con mi pregunta, y finalmente me responderás siguiendo las indicaciones dadas.

------

## **Contexto:**

Soy un estudiante que está aprendiendo JavaScript desde sus fundamentos. Aunque ya utilizo `var`, `let` y `const` en ejercicios básicos, me cuesta comprender la diferencia conceptual entre los tres tipos de declaración.

------

## **Entrada:**

Voy a darte una pregunta puntual para que me expliques el concepto a nivel de caso de estudio. La enviaré directamente como prompt.

------

## **Salida:**

Me responderás con una explicación pedagógica a nivel de caso práctico, mezclando teoría con ejemplos codificables y razonamiento paso a paso, alineado con el código generado.

------

## **Ejemplo :**

```javascript
let age = 20;
age = 21;
console.log(age); // 21

const name = "Vale";
console.log(name); // "Vale"

var country = "Colombia";
country = "Brasil";
console.log(country); // "Brasil"
```

En donde:

1. Se declaran variables usando `let`, `const` y `var`.
2. Algunas variables cambian su valor durante la ejecución.
3. El programa muestra los valores finales en consola.

------

## **Pregunta #1**
¿Cuál es la diferencia fundamental entre `let` y `const` en JavaScript?
---
# Prompt 2
## **Instrucción:**

Vas a actuar como un docente de programación para estudiantes jóvenes que están comenzando en JavaScript. Te daré un contexto, una entrada y deberás responder con un estilo pedagógico basado en casos prácticos.

------

## **Contexto:**

Estoy aprendiendo diferentes formas de declarar funciones en JavaScript. Entiendo la sintaxis, pero no comprendo del todo cómo funciona el contexto `this` en las arrow functions.

------

## **Entrada:**

Te enviaré preguntas puntuales relacionadas al concepto para que las expliques de manera clara en forma de estudio de caso aplicable.

------

## **Salida:**

Me explicarás el concepto mezclando teoría con un ejemplo codificable, junto con razonamiento que conecte la teoría con la práctica.

------

## **Ejemplo :**

```javascript
const user = {
  name: "Vale",
  normalFunction: function () {
    return this.name;
  },
  arrowFunction: () => {
    return this.name;
  }
};

console.log(user.normalFunction()); 
console.log(user.arrowFunction());
```

1. Se crea un objeto con dos métodos diferentes.
2. Ambos intentan acceder a la propiedad `name`.
3. Los resultados en consola son distintos.

------

## **Pregunta #2**

¿Qué característica técnica distingue a las arrow functions de las funciones tradicionales?
---
# Prompt 3
## **Instrucción:**

Actúa como docente de programación para estudiantes que inician en JavaScript. Te daré un contexto y luego una pregunta. Responderás combinando teoría, ejemplo codificable y razonamiento pedagógico.

------

## **Contexto:**

Estoy estudiando métodos de arrays y he visto `map()`, pero no termino de entender claramente qué hace ni por qué crea un nuevo array.

------

## **Entrada:**

Te enviaré la pregunta principal usando el concepto del prompt original.

------

## **Salida:**

Responderás con una explicación clara y un ejemplo práctico alineado a la teoría.

------

## **Ejemplo:**

```javascript
const numbers = [1, 2, 3];
const doubled = numbers.map(num => num * 2);

console.log(doubled); 
console.log(numbers);
```

1. Se tiene un array original con números.
2. Se aplica el método `map()` con una operación.
3. Se obtienen dos arrays diferentes al imprimir.

------

## **Pregunta #3**

¿Cuál es la función principal del método `map()` en JavaScript?
---
# Prompt 4
## **Instrucción:**

Vas a actuar como docente de JavaScript para resolver dudas conceptuales mediante explicaciones basadas en casos prácticos.

------

## **Contexto:**

Estoy aprendiendo programación asíncrona y me han explicado las promesas, pero aún no tengo claro para qué se usan y qué representan.

------

## **Entrada:**

Te mandaré la pregunta puntual según el concepto solicitado.

------

## **Salida:**

Responderás con teoría combinada con ejemplo práctico de uso real.

------

## **Ejemplo:**

```javascript
const fetchData = new Promise((resolve, reject) => {
  setTimeout(() => resolve("Datos recibidos"), 1000);
});

fetchData.then(data => console.log(data));
console.log("Esperando...");
```

1. Se crea una operación que tarda un tiempo en completarse.
2. El código continúa ejecutándose inmediatamente.
3. El resultado aparece después en la consola.

------

## **Pregunta #4**

¿Para qué se utilizan las promesas en JavaScript?
---
# Prompt 5
## **Instrucción:**

Actúa como docente de JavaScript y explícame los conceptos que no entiendo usando teoría más ejemplos prácticos aplicables a casos reales.

------

## **Contexto:**

Estoy empezando a trabajar con el DOM, pero no entiendo qué tipo de modificaciones puede hacer JavaScript sobre una página web.

------

## **Entrada:**

Te enviaré una pregunta puntual relacionada con este concepto.

------

## **Salida:**

Me responderás con explicación conceptual más un ejemplo codificable y una breve argumentación.

------

## **Ejemplo:**

```javascript
const title = document.getElementById("title");
title.textContent = "Nuevo título";
title.style.color = "blue";
title.classList.add("resaltado");

console.log(title);
```

1. Se selecciona un elemento HTML del documento.
2. Se realizan varias operaciones sobre ese elemento.
3. El elemento queda modificado de alguna forma.

------

## **Pregunta #5**

¿Qué capacidades ofrece JavaScript para manipular el DOM?
---
# Prompt 6
## **Instrucción:**

Vas a actuar como un docente de programación para estudiantes de 17-24 años enfocado en JavaScript. Te proporcionaré un contexto y luego una pregunta puntual. Tu respuesta deberá ser pedagógica, mezclando teoría con un ejemplo codificable y explicaciones paso a paso.

------

## **Contexto:**

Estoy aprendiendo estructuras de datos básicas en JavaScript, y aunque ya utilicé objetos, aún no comprendo claramente qué son y cómo almacenan información mediante pares clave-valor.

------

## **Entrada:**

Te enviaré una pregunta específica relacionada con la definición de un objeto en JavaScript.

------

## **Salida:**

Me responderás con una explicación conceptual acompañada de un ejemplo práctico que refleje la estructura y uso real de un objeto.

------

## **Ejemplo:**

```javascript
const user = {
  name: "Vale",
  age: 21,
  country: "Colombia"
};

console.log(user.name);
console.log(user["age"]);
console.log(user);
```

1. Se crea una estructura que agrupa información relacionada.
2. Se puede acceder a los datos de diferentes maneras.
3. La estructura completa se puede visualizar en consola.

------

## **Pregunta #6**

¿Qué es un objeto en JavaScript y cómo almacena información?
---
# Prompt 7
## **Instrucción:**

Actúa como docente de JavaScript y explícame conceptos usando teoría acompañada de ejemplos aplicados. Te daré un contexto y luego la pregunta principal.

------

## **Contexto:**

Estoy aprendiendo métodos de arrays y no comprendo completamente cómo funciona `filter()` ni qué criterio utiliza para seleccionar elementos.

------

## **Entrada:**

Te enviaré una pregunta puntual basada en este concepto.

------

## **Salida:**

Responde combinando explicación conceptual con un ejemplo codificable alineado con el comportamiento del método.

------

## **Ejemplo:**

```javascript
const numbers = [1, 2, 3, 4, 5];
const evens = numbers.filter(num => num % 2 === 0);

console.log(evens);
console.log(numbers);
console.log(evens.length);
```

1. Se parte de un array con varios elementos.
2. Se aplica el método `filter()` con una condición.
3. Se obtiene un nuevo array con menos elementos que el original.

------

## **Pregunta #7**

¿Cuál es la función del método `filter()` en JavaScript?
---
# Prompt 8
## **Instrucción:**

Vas a enseñarme JavaScript como un docente, mezclando teoría, ejemplo de código y explicación razonada detrás de cada concepto.

------

## **Contexto:**

He escuchado que JSON se usa para transmitir información, pero no entiendo qué es exactamente ni por qué es tan común.

------

## **Entrada:**

Formularé una pregunta concreta sobre este concepto.

------

## **Salida:**

Responderás con explicación teórica acompañada de un ejemplo práctico relacionado al uso de JSON.

------

## **Ejemplo:**

```javascript
const user = {
  name: "Vale",
  age: 21
};

const jsonString = JSON.stringify(user);
console.log(jsonString);
console.log(typeof jsonString);

const backToObject = JSON.parse(jsonString);
console.log(backToObject);
console.log(typeof backToObject);
```

1. Se tiene un objeto de JavaScript con datos.
2. Se realizan transformaciones sobre ese objeto.
3. Los tipos de dato cambian durante el proceso.

------

## **Pregunta #8**

¿Qué es JSON y para qué se utiliza?
---
# Prompt 9
## **Instrucción:**

Actúa como un docente de JavaScript. Te daré un contexto, luego una pregunta, y deberás responder con teoría y un ejemplo aplicable al caso.

------

## **Contexto:**

Estoy aprendiendo métodos avanzados de arrays y no logro entender cómo `reduce()` puede transformar un arreglo completo en un solo valor final.

------

## **Entrada:**

Te enviaré una pregunta basada en este concepto.

------

## **Salida:**

Responderás con teoría más un ejemplo de código que explique la función acumuladora.

------

## **Ejemplo:**

```javascript
const numbers = [1, 2, 3, 4];

const sum = numbers.reduce((acc, num) => acc + num, 0);

console.log(numbers);
console.log(sum);
console.log(typeof sum);
```

1. Se tiene un array con múltiples valores.
2. Se aplica el método `reduce()` con una operación.
3. El resultado final es un único valor diferente al array original.

------

## **Pregunta #9**

¿Para qué se utiliza el método `reduce()` en JavaScript?
---
# Prompt 10
## **Instrucción:**

Vas a actuar como docente experto en JavaScript y responderás mis preguntas mezclando teoría con ejemplos codificables.

------

## **Contexto:**

He visto el valor especial `NaN`, pero no entiendo por qué aparece ni qué representa exactamente dentro del lenguaje.

------

## **Entrada:**

Haré una pregunta puntual basada en este concepto.

------

## **Salida:**

Responderás con una explicación clara acompañada de un ejemplo práctico.

------

## **Ejemplo:**

```javascript
const invalid = Number("hola");
console.log(invalid);
console.log(typeof invalid);

const result = 0 / 0;
console.log(result);

console.log(invalid === result);
```

1. Se intentan realizar operaciones numéricas con valores no numéricos.
2. JavaScript devuelve un valor especial.
3. Ese valor se comporta de manera particular en comparaciones.

------

## **Pregunta #10**

¿Qué representa el valor `NaN` en JavaScript?
---
# Prompt 11
## nstrucción:**

Vas a actuar como un docente de programación especializado en JavaScript. Te entregaré un contexto y luego una pregunta puntual. Tu respuesta deberá combinar teoría, ejemplo codificable y explicación argumentada.

------

## **Contexto:**

Estoy aprendiendo sobre operadores de comparación y no comprendo completamente en qué se diferencian `===` y `==`, ni por qué uno es más recomendado que el otro.

------

## **Entrada:**

Te enviaré una pregunta puntual sobre este concepto para que lo expliques a nivel de caso práctico.

------

## **Salida:**

Me responderás con una explicación teórica acompañada de un ejemplo codificable que evidencie la diferencia entre ambos operadores.

------

## **Ejemplo:**

```javascript
console.log(5 == "5");
console.log(5 === "5");

console.log(true == 1);
console.log(true === 1);

console.log(0 == false);
console.log(0 === false);
```

1. Se realizan varias comparaciones entre valores.
2. Algunos valores parecen iguales pero tienen tipos diferentes.
3. Los resultados varían dependiendo del operador usado.

------

## **Pregunta #11**

¿Cuál es la diferencia entre los operadores `===` y `==` en JavaScript?
---
# Prompt 12
## **Instrucción:**

Actúa como un docente de programación para estudiantes jóvenes. Te proporcionaré un contexto y luego una pregunta. Deberás responder usando teoría más un ejemplo práctico.

------

## **Contexto:**

Estoy empezando a escuchar sobre APIs, pero no comprendo qué son exactamente ni cómo permiten que distintas aplicaciones se comuniquen.

------

## **Entrada:**

Te enviaré la pregunta puntual sobre este concepto.

------

## **Salida:**

Responderás con teoría clara más un ejemplo práctico que represente el intercambio de datos mediante APIs.

------

## **Ejemplo:**

```javascript
// Ejemplo de consumo de una API
fetch("https://api.example.com/user/1")
  .then(response => response.json())
  .then(data => console.log(data));

console.log("Solicitando datos...");
```

1. Se hace una solicitud a una dirección web específica.
2. El programa espera una respuesta estructurada.
3. Los datos llegan y se procesan automáticamente.

------

## **Pregunta #12**

¿Qué es una API y cuál es su función principal?
---
# Prompt 13
## **Instrucción:**

Vas a actuar como docente de JavaScript aplicando teoría y ejemplos prácticos basados en casos reales. Recibirás un contexto y luego una pregunta puntual.

------

## **Contexto:**

Estoy aprendiendo sobre procesos asíncronos y no entiendo muy bien qué significa que algo se ejecute sin bloquear el programa.

------

## **Entrada:**

Te enviaré una pregunta directamente relacionada con este concepto.

------

## **Salida:**

Responderás con una explicación clara acompañada de un ejemplo funcional que muestre cómo funciona una operación asíncrona.

------

## **Ejemplo:**

```javascript
console.log("Inicio");

setTimeout(() => {
  console.log("Operación terminada");
}, 2000);

console.log("Fin");

for(let i = 0; i < 3; i++) {
  console.log("Contando:", i);
}
```

1. El programa ejecuta varias instrucciones en secuencia.
2. Una operación está configurada para ejecutarse más tarde.
3. El programa no se detiene esperando y continúa con otras tareas.

------

## **Pregunta #13**

¿Qué significa que un proceso sea asíncrono en JavaScript?
---
# Prompt 14
## **Instrucción:**

Actúa como docente especializado en conceptos del DOM. Te entregaré un contexto y una pregunta puntual. Tu explicación deberá incluir teoría, ejemplo codificable y razonamiento.

------

## **Contexto:**

Estoy estudiando la estructura del DOM y veo que todo se basa en nodos, pero no entiendo exactamente qué representan ni qué tipos existen.

------

## **Entrada:**

Enviaré la pregunta específica para que la desarrolles a nivel de caso práctico.

------

## **Salida:**

Me responderás con teoría clara y un ejemplo de código que muestre el concepto de nodos.

------

## **Ejemplo:**

```javascript
const title = document.getElementById("title");

console.log(title.nodeType);
console.log(title.nodeName);
console.log(title.firstChild.nodeType);
console.log(title.childNodes.length);
```

1. Se selecciona un elemento del documento HTML.
2. Se inspeccionan diferentes propiedades relacionadas con su estructura.
3. Cada propiedad devuelve valores numéricos o textuales específicos.

------

## **Pregunta #14**

¿Qué representa un nodo en el DOM?
---
# Prompt 15
## **Instrucción:**

Vas a actuar como docente experto en JavaScript. Te daré un contexto y luego una pregunta que deberás responder con teoría, ejemplo codificable y razonamiento.

------

## **Contexto:**

He empezado a usar `localStorage`, pero no entiendo exactamente para qué sirve ni qué tipo de persistencia maneja.

------

## **Entrada:**

Te enviaré la pregunta puntual sobre este concepto.

------

## **Salida:**

Tu respuesta deberá combinar teoría con un ejemplo aplicable y explicación clara.

------

## **Ejemplo:**

```javascript
localStorage.setItem("name", "Vale");
console.log(localStorage.getItem("name"));

// Cierra el navegador y vuelve a ejecutar:
console.log(localStorage.getItem("name"));

localStorage.removeItem("name");
console.log(localStorage.getItem("name"));
```

1. Se guardan datos usando un mecanismo del navegador.
2. Los datos persisten después de cerrar y abrir el navegador.
3. Los datos se pueden eliminar manualmente cuando ya no se necesitan.

------

## **Pregunta #15**

¿Para qué sirve `localStorage` en JavaScript?
---
# Prompt 16
## **Instrucción:**

Vas a actuar como un docente de programación especializado en JavaScript. Te daré un contexto y luego una pregunta puntual. Responderás usando teoría, un ejemplo codificable y una explicación clara basada en un caso práctico.

------

## **Contexto:**

Estoy aprendiendo sobre mecanismos de almacenamiento en el navegador. Ya vi `localStorage`, pero ahora quiero entender cómo `sessionStorage` se diferencia en cuanto a persistencia.

------

## **Entrada:**

Enviaré una pregunta específica relacionada con la diferencia entre `sessionStorage` y `localStorage`.

------

## **Salida:**

Me responderás con teoría y un ejemplo práctico que muestre cómo funciona `sessionStorage` y cuál es su principal diferencia con `localStorage`.

------

## **Ejemplo:**

```javascript
sessionStorage.setItem("tempName", "Vale");
localStorage.setItem("permName", "Vale");

console.log(sessionStorage.getItem("tempName"));
console.log(localStorage.getItem("permName"));

// Cierra la pestaña y abre una nueva, luego ejecuta:
console.log(sessionStorage.getItem("tempName"));
console.log(localStorage.getItem("permName"));
```

1. Se guardan datos en dos mecanismos diferentes del navegador.
2. Ambos funcionan similar en principio.
3. Al cerrar y abrir el navegador, uno de los datos desaparece.

------

## **Pregunta #16**

¿En qué se diferencia `sessionStorage` de `localStorage`?
---
# Prompt 17
## **Instrucción:**

Vas a actuar como un docente de JavaScript y deberás explicar conceptos de forma teórica y práctica usando ejemplos aplicables a casos reales.

------

## **Contexto:**

Estoy aprendiendo sobre funciones y escuché que un "callback" es clave en JavaScript, pero no comprendo realmente qué es ni cuándo se ejecuta.

------

## **Entrada:**

Te enviaré la pregunta puntual sobre este concepto.

------

## **Salida:**

Responderás con teoría más ejemplo codificable que muestre cuándo se ejecuta un callback.

------

## **Ejemplo:**

```javascript
function greet(name, callback) {
  console.log("Hola " + name);
  callback();
}

greet("Vale", () => {
  console.log("Este mensaje viene de la segunda función");
});

console.log("Programa terminado");
```

1. Se define una función que recibe dos parámetros.
2. Uno de los parámetros es otra función.
3. El orden de ejecución de los mensajes sigue un patrón específico.

------

## **Pregunta #17**

¿Qué es un callback en JavaScript?
---
# Prompt 18
## **Instrucción:**

Actúa como docente para estudiantes que inician en JavaScript. Te daré un contexto y una pregunta puntual. Responderás con teoría y ejemplo codificable.

------

## **Contexto:**

Estoy estudiando sobre estructuras de datos y he visto que un array puede guardar múltiples elementos, pero no tengo claro su definición precisa ni qué tipo de valores puede contener.

------

## **Entrada:**

Enviaré una pregunta directa sobre la definición de un array.

------

## **Salida:**

Responderás con teoría más un ejemplo práctico que refleje la estructura del array.

------

## **Ejemplo:**

```javascript
const items = [1, "Hola", true, { name: "Vale" }, [1, 2, 3]];

console.log(items[0]);
console.log(items[1]);
console.log(items[3].name);
console.log(items[4][1]);
console.log(items.length);
```

1. Se crea una estructura que contiene múltiples valores.
2. Los valores pueden ser de diferentes tipos.
3. Se puede acceder a cada valor usando su posición.

------

## **Pregunta #18**

¿Qué es un array en JavaScript?
---
# Prompt 19
## **Instrucción:**

Vas a actuar como un docente de JavaScript. Te daré un contexto y una pregunta puntual. Responderás combinando teoría con ejemplo codificable y explicación aplicada.

------

## **Contexto:**

Estoy aprendiendo a convertir valores y strings y vi la función `parseInt()`, pero no comprendo cómo interpreta el texto ni qué hace exactamente.

------

## **Entrada:**

Enviaré la pregunta puntual sobre `parseInt()`.

------

## **Salida:**

Responderás con teoría clara más un ejemplo demostrativo.

------

## **Ejemplo:**

```javascript
console.log(parseInt("123abc"));
console.log(parseInt("42"));
console.log(parseInt("hola"));
console.log(parseInt("99 botellas"));

const texto = "456";
const numero = parseInt(texto);
console.log(typeof texto);
console.log(typeof numero);
```

1. Se procesan diferentes cadenas de texto con números.
2. Algunas cadenas tienen solo números, otras mezclan letras.
3. Los resultados y tipos de dato varían según el contenido.

------

## **Pregunta #19**

¿Qué hace la función `parseInt()` en JavaScript?
---
# Prompt 20
## **Instrucción:**

Vas a actuar como docente especializado en funciones temporizadas de JavaScript. Te daré un contexto y luego una pregunta puntual. Responderás con teoría, ejemplo codificable y explicación razonada.

------

## **Contexto:**

Estoy aprendiendo programación asíncrona y escuché que `setTimeout()` permite ejecutar algo luego de un tiempo, pero no comprendo cómo se usa.

------

## **Entrada:**

Te enviaré una pregunta puntual sobre este concepto.

------

## **Salida:**

Responderás con teoría más un ejemplo práctico de uso real del temporizador.

------

## **Ejemplo:**

```javascript
console.log("Inicio");

setTimeout(() => {
  console.log("Han pasado 2 segundos");
}, 2000);

console.log("Fin");

setTimeout(() => {
  console.log("Han pasado 1 segundo");
}, 1000);
```

1. El programa ejecuta varias instrucciones en secuencia.
2. Algunas funciones están configuradas con diferentes tiempos.
3. Los mensajes aparecen en un orden específico en la consola.

------

## **Pregunta #20**

¿Para qué sirve `setTimeout()` en JavaScript?
---
# Prompt 21
## **Instrucción:**

Vas a actuar como un docente de programación especializado en JavaScript. Te proporcionaré un contexto y una pregunta puntual. Tu explicación deberá combinar teoría, ejemplo codificable y razonamiento paso a paso.

------

## **Contexto:**

Estoy aprendiendo sobre funciones temporizadas y entiendo `setTimeout()`, pero ahora quiero comprender cómo funciona `setInterval()` y en qué se diferencia de una ejecución única.

------

## **Entrada:**

Enviaré la pregunta puntual sobre este concepto.

------

## **Salida:**

Responderás con teoría clara y un ejemplo práctico de cómo `setInterval()` ejecuta una función repetidamente.

------

## **Ejemplo:**

```javascript
let count = 0;

const intervalId = setInterval(() => {
  count++;
  console.log("Conteo:", count);
  
  if (count === 3) {
    clearInterval(intervalId);
    console.log("Intervalo detenido");
  }
}, 1000);

console.log("Intervalo iniciado");
```

1. Se configura una operación que se repite cada cierto tiempo.
2. Un contador se incrementa en cada ejecución.
3. La repetición se puede detener bajo una condición específica.

------

## **Pregunta #21**

¿Qué hace la función `setInterval()` en JavaScript?
---
# Prompt 22
## **Instrucción:**

Actúa como docente experto en fundamentos de JavaScript. Te daré un contexto y luego una pregunta puntual. Responderás combinando teoría con ejemplo codificable y explicación argumentada.

------

## **Contexto:**

Estoy aprendiendo cómo el motor de JavaScript procesa el código y escuché sobre el hoisting, pero no entiendo cómo funciona ni qué cosas son "elevadas".

------

## **Entrada:**

Enviaré una pregunta directa sobre este concepto.

------

## **Salida:**

Responderás con teoría más un ejemplo práctico que ilustre claramente el comportamiento del hoisting.

------

## **Ejemplo:**

```javascript
console.log(a);
var a = 5;
console.log(a);

sayHi();

function sayHi() {
  console.log("Hola!");
}

// Para let/const, mejor ejemplo:
console.log(typeof c); // undefined, no lanza error
let c = 10;
```

1. Se intentan usar variables antes de declararlas.
2. Se llama a una función antes de su definición.
3. Algunos casos funcionan y otros generan errores.

------

## **Pregunta #22**

¿Qué es el hoisting en JavaScript?
---
# Prompt 23
## **Instrucción:**

Vas a actuar como un docente de programación orientada a objetos en JavaScript. Recibirás un contexto y una pregunta, y deberás responder mezclando teoría y ejemplo codificable.

------

## **Contexto:**

Estoy estudiando programación orientada a objetos y vi que JavaScript usa clases, pero aún no entiendo qué son exactamente ni para qué se utilizan.

------

## **Entrada:**

Enviaré la pregunta puntual sobre el concepto de clase.

------

## **Salida:**

Responderás con teoría clara acompañada de un ejemplo práctico de cómo se define y usa una clase.

------

## **Ejemplo:**

```javascript
class Person {
  constructor(name, age) {
    this.name = name;
    this.age = age;
  }

  greet() {
    console.log(`Hola, soy ${this.name}`);
  }
}

const user1 = new Person("Vale", 21);
const user2 = new Person("Ana", 25);

user1.greet();
user2.greet();
console.log(user1.age);
```

1. Se define una estructura con la palabra clave `class`.
2. Se crean múltiples elementos a partir de esa estructura.
3. Cada elemento tiene sus propios valores pero comparte comportamiento.

------

## **Pregunta #23**

¿Qué es una clase en JavaScript?
---
# Prompt 24
## **Instrucción:**

Vas a actuar como docente especializado en sintaxis moderna de JavaScript. Te proporcionaré un contexto y una pregunta. Tu respuesta deberá incluir teoría, ejemplo práctico y razonamiento.

------

## **Contexto:**

Estoy aprendiendo sobre nuevas características de ES6 y vi el operador spread, pero no termino de entender para qué sirve ni cómo se usa en arrays u objetos.

------

## **Entrada:**

Enviaré la pregunta puntual basada en este concepto.

------

## **Salida:**

Responderás con teoría combinada con un ejemplo codificable y explicación clara.

------

## **Ejemplo:**

```javascript
const numbers = [1, 2, 3];
const moreNumbers = [...numbers, 4, 5];
console.log(numbers);
console.log(moreNumbers);

const user = { name: "Vale", age: 21 };
const updatedUser = { ...user, country: "Colombia" };
console.log(user);
console.log(updatedUser);
```

1. Se tienen estructuras de datos originales (arrays y objetos).
2. Se crean nuevas estructuras usando la sintaxis `...`.
3. Las estructuras originales y las nuevas son independientes.

------

## **Pregunta #24**

¿Para qué sirve el operador spread (`...`) en JavaScript?
---
# Prompt 25
## **Instrucción:**

Actúa como docente experto en asincronía en JavaScript. Te daré un contexto y luego una pregunta puntual. Responderás mezclando teoría, código y explicación clara.

------

## **Contexto:**

Estoy estudiando cómo funcionan las promesas y aprendí que se pueden encadenar, pero no entiendo cómo este encadenamiento ayuda a ordenar procesos asíncronos.

------

## **Entrada:**

Enviaré la pregunta puntual sobre este concepto.

------

## **Salida:**

Me responderás con teoría más un ejemplo codificable que muestre una cadena de promesas en acción.

------

## **Ejemplo:**

```javascript
fetchUser()
  .then(user => getPosts(user.id))
  .then(posts => getComments(posts[0].id))
  .then(comments => console.log(comments));

function fetchUser() {
  return Promise.resolve({ id: 1, name: "Vale" });
}

function getPosts(userId) {
  return Promise.resolve([{ id: 10, title: "Mi post" }]);
}

function getComments(postId) {
  return Promise.resolve(["Buen post", "Interesante"]);
}
```

1. Se tienen varias funciones que retornan promesas.
2. Se conectan usando `.then()` en secuencia.
3. Cada función recibe el resultado de la anterior.

------

## **Pregunta #25**

¿Qué permite hacer una promise chain en JavaScript?
---
# Prompt 26
## **Instrucción:**

Vas a actuar como un docente especializado en JavaScript. Te proporcionaré un contexto y luego una pregunta puntual. Tu respuesta deberá mezclar teoría, ejemplo codificable y explicación pedagógica basada en un caso práctico.

------

## **Contexto:**

Estoy aprendiendo a manejar errores en JavaScript y escuché que `try...catch` se usa para evitar que el programa se detenga, pero no comprendo claramente cómo funciona.

------

## **Entrada:**

Enviaré una pregunta específica sobre este concepto.

------

## **Salida:**

Responderás con teoría clara acompañada de un ejemplo que muestre el manejo de errores en acción.

------

## **Ejemplo:**

```javascript
try {
  const result = JSON.parse("{ nombre: 'Vale' }");
  console.log(result);
  console.log("Todo salió bien");
} catch (error) {
  console.log("Hubo un problema:", error.message);
}

console.log("El programa continúa");
```

1. Se intenta ejecutar código que puede fallar.
2. Si hay un error, el flujo cambia a otra sección.
3. El programa no se detiene y continúa ejecutándose.

------

## **Pregunta #26**

¿Para qué sirve la estructura `try...catch` en JavaScript?
---
# Prompt 27
## **Instrucción:**

Vas a actuar como un docente de JavaScript enfocado en enseñar sintaxis moderna. Te daré un contexto y luego una pregunta. Tu explicación deberá incluir teoría, ejemplo codificable y justificación del uso.

------

## **Contexto:**

Estoy empezando a usar strings y vi que las plantillas literales (`template literals`) permiten insertar variables, pero no entiendo exactamente cómo funcionan.

------

## **Entrada:**

Enviaré la pregunta puntual sobre este concepto.

------

## **Salida:**

Responderás mezclando teoría con un ejemplo práctico que muestre la interpolación de variables.

------

## **Ejemplo:**

```javascript
const name = "Vale";
const age = 21;

const message1 = "Hola, mi nombre es " + name + " y tengo " + age + " años.";
const message2 = `Hola, mi nombre es ${name} y tengo ${age} años.`;

console.log(message1);
console.log(message2);
console.log(message1 === message2);
```

1. Se crean dos mensajes usando diferentes sintaxis.
2. Ambos mensajes usan las mismas variables.
3. Los resultados son idénticos pero la forma de escribirlos difiere.

------

## **Pregunta #27**

¿Para qué sirven las plantillas literales en JavaScript?
---
# Prompt 28
## **Instrucción:**

Actúa como docente experto en métodos de arrays. Te daré un contexto y luego una pregunta puntual. Tu respuesta deberá combinar teoría, código y explicación clara.

------

## **Contexto:**

Estoy aprendiendo métodos de búsqueda en arrays y escuché que `find()` devuelve el primer elemento que cumple una condición, pero no entiendo cómo funciona.

------

## **Entrada:**

Enviaré una pregunta puntual basada en este concepto.

------

## **Salida:**

Responderás con teoría más un ejemplo codificable para mostrar cómo opera `find()`.

------

## **Ejemplo:**

```javascript
const users = [
  { id: 1, name: "Vale" },
  { id: 2, name: "Ana" },
  { id: 3, name: "Luis" }
];

const found = users.find(user => user.id === 2);
const notFound = users.find(user => user.id === 99);

console.log(found);
console.log(notFound);
console.log(typeof found);
console.log(typeof notFound);
```

1. Se tiene un array con múltiples objetos.
2. Se busca un elemento usando una condición.
3. El resultado varía dependiendo de si existe o no el elemento.

------

## **Pregunta #28**

¿Qué hace el método `find()` en JavaScript?
---
# Prompt 29
## **Instrucción:**

Vas a actuar como un docente especializado en métodos de arrays y strings. Te daré un contexto y luego una pregunta puntual. Responderás con teoría, ejemplo codificable y explicación clara.

------

## **Contexto:**

Estoy aprendiendo a verificar valores en estructuras y vi el método `includes()`, pero no sé si funciona igual en arrays y en strings.

------

## **Entrada:**

Enviaré una pregunta específica basada en este concepto.

------

## **Salida:**

Me responderás con teoría clara y un ejemplo práctico para cada caso.

------

## **Ejemplo:**

```javascript
const numbers = [1, 2, 3, 4, 5];
console.log(numbers.includes(2));
console.log(numbers.includes(10));

const text = "Hola Vale";
console.log(text.includes("Vale"));
console.log(text.includes("Ana"));

console.log(typeof numbers.includes(2));
```

1. Se verifican valores dentro de diferentes estructuras.
2. Algunas búsquedas encuentran el valor, otras no.
3. El tipo de resultado es siempre el mismo independiente del caso.

------

## **Pregunta #29**

¿Para qué sirve el método `includes()` en JavaScript?
---
# Prompt 30
## **Instrucción:**

Actúa como docente de programación asíncrona en JavaScript. Te daré un contexto y luego una pregunta puntual. Tu explicación debe combinar teoría con ejemplo codificable.

------

## **Contexto:**

Estoy aprendiendo a trabajar con promesas y escuché que una función marcada como `async` puede usar `await`, pero no entiendo qué ventaja ofrece.

------

## **Entrada:**

Enviaré la pregunta directa basada en este concepto.

------

## **Salida:**

Responderás con teoría clara más un ejemplo codificable que muestre el uso de `async` y `await`.

------

## **Ejemplo:**

```javascript
async function getData() {
  const promise = new Promise(resolve => {
    setTimeout(() => resolve("Datos cargados"), 1000);
  });

  console.log("Esperando...");
  const result = await promise;
  console.log(result);
  return result;
}

getData();
console.log("Función llamada");
```

1. Se define una función con la palabra clave `async`.
2. Dentro se usa `await` con una promesa.
3. El orden de ejecución de los mensajes sigue un patrón particular.

------

## **Pregunta #30**

¿Qué permite usar una función marcada como `async` en JavaScript?
