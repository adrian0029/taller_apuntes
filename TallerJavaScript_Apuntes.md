<!--Lenguaje Markdown:
Objetivo:Proporcionar una herramienta para documentar codigo,
 o aspectos tecnicos para compartirlos o tenerlos de referencia
  en mi GIT u otra plataforma-->

 <!--Markdown es un lenguaje de marcado ligerio creado en 2004 por Jonh Gruber
 trata de conseguirla maxima legibilidad

 facilidad de publicacion tanto en su forma de entrada y de salida, inspirandose
 en muchas convenciones existentes para marcar mensajes de correo electronico
 usando texto plano.

 El objetivo de su creador fue que la gente puediera escribir usando un formato de
 texto plano facil de leer, facil de escribir y con la posibilidad de convertir su
 documento en htl valido.

 La gran simpleza de su sintaxis hizo que tuviera una rapida adopcion y popularidad
 en la comunidad de desarrolladores.

 Actualmente permite generar contenido HTML de forma dinamica.

 Conocer Sintaxis MarkDown
 1.- Parrafos [Parrafo 1...]-->

 Parrafo 1...
 "Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo.

 _cursiva_
 **negrita**

 ~tachado~

 **_cursiva y negrita_**

 _~cursiva y tachado~_

 **~negrita y tachado~**

 **_~cursiva, negrita y tachado~_**
Encabezados
 # Encabezado nivel 1
 ## Encabezado nivel 2
 ### Encabezado nivel 3
 #### Encabezado nivel 4
 ##### Encabezado nivel 5
 ###### Encabezado nivel 6

Divisiones

Un bloque de contenido
---
Este es otro bloque de contenido

Listas: Podemos utilizar las listas ordenadas y listas desordenadas

1. html5
1. css
1. javascript
1. Ajax
1. Json

- html5
- css
- javascript
- ajax
- json

citas
podemos dar formato de cita a un texto anteponiendo a la linea de texto
un caracter de mayor que(>).

>La IA en el futuro remplazara a muchas profesiones de TI. - Adrian

>ChatGPT debe potenciar mi aprendizaje, no suprimir mi estado autodidacta
>
>Adrian

Enlaces
[Youtube](https://www.youtube.com)
[Enlace a google](https://www.google.com)

Imagenes
![Texto alternativo](URLdelaImagen)

Tablas

| columna1 | columna2 | columna 3 |
| -------- | -------- | --------- |
| A        | B        | C         |
| D        | E        | F         |
| G        | H        | I         |

Codigo
Podemos dar formato a un texto, para ello se usa el acento grave(`).

Esto es un `codigo` en linea.

En javaScript_una variable se define asi:
`let saludo = "Hola Mundo";`

pero si queremos sacar un bloque completo de codigo utilizamos':
```js
let estudiante="Adrian Mtz";
let edad="30";
let isEstudiante=true;
let calificacion=90.2;

// 1.- Operadores aritmeticos

let a=10;
let b=5;
    console.log(a+b);
    console.log(a-b);
    console.log(a*b);
    console.log(a/b);
    console.log(a%b);

//Operadores de asignacion

let x=10;
x += 5;
x -= 2;
x *= 3;
x /= 3;
x %= 5;
 
// Operadores de Comparacion

let aa=5; let bb='5';
console.log(a == b);
console.log(a === b);
console.log(a != b);
console.log(a !== b);
console.log(a > 3);

//operadores logicos
let d=true;
let t=false;
```
