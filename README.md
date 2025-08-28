Este es mi primer proyecto en HTML, CSS y JavaScript.  
Aquí practico cosas básicas como:

- Encabezados y párrafos en HTML  
- Uso de enlaces e imágenes  
- Estilos básicos con CSS (colores, fuentes y alineación)  
- Un botón que al hacer clic muestra un mensaje en la consola con JavaScript  

El título de la página es **"Mi Primera Página"** y contiene una pequeña descripción personal, un enlace a mi Instagram, una imagen y un botón interactivo.  

📚 Fundamentos de Desarrollo Web
Este documento proporciona una visión general de las tecnologías fundamentales para el desarrollo web: HTML, CSS, y JavaScript. Además, cubre conceptos clave como variables de entorno y el uso de las Herramientas de Desarrollo de Chrome.

💻 HTML: Lenguaje de Marcado de Hipertexto
HTML (HyperText Markup Language) es el lenguaje estándar para crear páginas web. Utiliza etiquetas para organizar y presentar texto, imágenes, videos y otros elementos, definiendo la estructura y el contenido de un sitio. Su función principal es:

1.Definir la estructura.

2.Incorporar contenido.

3.Crear enlaces.

4.Proporcionar semántica.

Esto permite que los navegadores interpreten y muestren el contenido de forma coherente.

🏷️Etiquetas HTML
Las etiquetas HTML son elementos clave que definen la estructura y el contenido de una página. Funcionan como marcadores que delimitan el inicio y el fin de un elemento, indicando al navegador cómo mostrarlo.

| Etiqueta | Descripción |
| :--- | :--- |
| `<a href="http://direccion">TEXTO</a>` | Un vínculo a una dirección web |
| `<b>TEXTO</b>` | El texto encerrado se mostrará en negrita |
| `<br>` | Un salto de línea |
| `<div></div>` | Contenedor o bloque, puede contener texto o cualquier otro elemento |
| `<em>TEXTO</em>` | El texto encerrado se mostrará en cursiva |
| `<h1>TEXTO</h1>` | Encierra un encabezado de una sección, desde h1 hasta el h6 |
| `<hr>` | Inserta una línea o división |
| `<i>TEXTO</i>` | El texto encerrado se mostrará en cursiva |
| `<img src="imagen.jpg" alt="">` | Inserta una imagen |
| `<input>` | Inserta una forma o control |
| `<input type="text">` | Entrada de texto |
| `<input type="button">` | Botón |
| `<input type="checkbox">` | Casilla |
| `<ol></ol>` o `<ul></ul>` | Lista ordenada o una lista desordenada |
| `<p>TEXTO</p>` | Inserta un párrafo |
| `<pre>TEXTO O CODIGO</pre>` | Muestra el texto pre-formateado |
| `<script></script>` | Inserta un código que ejecuta una función |
| `<span></span>` | Permite dar estructura al contenido |

🖥️Atributos de una etiqueta HTML
Un atributo es un par de nombre y valor que se añade a la etiqueta de apertura de un elemento para proporcionar información extra, modificar su comportamiento o apariencia.

| Atributo | Descripción |
| :--- | :--- |
| `id` | Identificador único para un elemento. |
| `class` | Define una o varias clases para aplicar estilos con CSS o manipular con JavaScript. |
| `style` | Permite aplicar estilos CSS en línea directamente al elemento. |
| `title` | Muestra un texto cuando el usuario pasa el mouse sobre el elemento (tooltip). |
| `alt` | Texto alternativo de una imagen (muy importante para accesibilidad y SEO). |
| `src` | Especifica la ruta de un recurso (usado en imágenes, scripts, videos, etc.). |
| `href` | Indica la dirección de un enlace (en `<a>` o `<link>`). |
| `target` | Define dónde se abre un enlace (`_blank`, `_self`, etc.). |
| `type` | Especifica el tipo de elemento (común en `<input>` o `<script>`). |
| `value` | Valor inicial de un campo de formulario o botón. |
| `name` | Identifica un elemento de formulario para enviarlo al servidor. |
| `placeholder` | Texto guía dentro de un campo de entrada. |
| `disabled` | Deshabilita un elemento de formulario para que no se pueda usar. |
| `checked` | Marca por defecto un checkbox o radio button. |
| `readonly` | Hace que un campo sea de solo lectura. |
| `maxlength` | Límite de caracteres en un campo de texto. |
| `width` / `height` | Tamaño de imágenes, videos o iframes. |
| `lang` | Define el idioma del contenido. |
| `data-*` | Atributos personalizados para almacenar datos adicionales en un elemento. |

🎨 CSS: Hojas de Estilo en Cascada
CSS (Cascading Style Sheets) es un lenguaje de estilos utilizado para dar cualidades visuales y estéticas a una página web.

Las tres formas principales de aplicar CSS en HTML son:

1.INLINE CSS: Dentro del mismo elemento usando el atributo style.
<p style="color: blue; font-size: 18px;">Texto en azul con tamaño 18px</p>

2.INTERNAL CSS: Dentro de la etiqueta <style> en el <head>.
<head>
  <style>
    p {
      color: green;
      font-size: 20px;
    }
  </style>
</head>

3.EXTERNAL CSS: En un archivo separado (styles.css) enlazado con <link>.
<link rel="stylesheet" href="styles.css">

/* styles.css */
body {
  background-color: #f4f4f4;
  font-family: Arial, sans-serif;
}

h1 {
  color: darkblue;
  text-align: center;
}

📍Propiedades CSS
Una propiedad en CSS es un atributo que se aplica a un elemento HTML para definir su estilo visual.

1.color: Define el color del texto.

2.font-size: Define el tamaño de la fuente.

3.background-color: Define el color de fondo.

4.Las propiedades se declaran dentro de un bloque de reglas con la siguiente estructura:
selector {
  propiedad: valor;
}

Otras propiedades comunes son:

1.font-family: Tipo de letra.

2.text-align: Alineación del texto.

3.margin: Márgenes externos.

4.padding: Espacio interno.

5.border: Bordes.

6.width / height: Ancho y alto.

7.display: Tipo de visualización (block, inline, flex, etc.).

Selectores CSS
Un selector es la parte de la regla CSS que indica a qué elementos HTML se aplicarán los estilos.

| Selector | Ejemplo | Descripción |
| :--- | :--- | :--- |
| Universal | `*` | Selecciona todos los elementos. |
| Por etiqueta | `p`, `h1`, `div` | Selecciona todos los elementos de ese tipo. |
| Por ID | `#id` | Selecciona un único elemento con ese ID. |
| Por clase | `.clase` | Selecciona todos los elementos con esa clase. |
| Descendiente | `div p` | Selecciona elementos dentro de otro. |
| Agrupados | `h1, h2, p` | Aplica el mismo estilo a varios elementos. |
| Atributo | `input[type="text"]` | Selecciona según un atributo. |

🤖 JavaScript (JS)
JavaScript es un lenguaje de programación que aporta interactividad y dinamismo a las páginas web. Funciona junto con HTML y CSS para crear una mejor experiencia de usuario.

Formas de añadir Interactividad
Insertando código en HTML:

Dentro de la etiqueta <script> en el documento.

Enlazando un archivo externo con <script src="app.js"></script>.

Usando eventos: Se asocian acciones a elementos (ej: onclick, onchange, onmouseover).

Manipulando el DOM: Con métodos como getElementById, querySelector, innerText, style, etc.

Datos Primitivos en JS
Son valores atómicos, inmutables y sin métodos.

1-string: Texto (ej: "Hola", 'Mundo').

2-number: Números enteros o decimales (ej: 42, 3.14).

3-boolean: Valores lógicos (true o false).

4-null: Valor intencionalmente vacío.

5-undefined: Valor no asignado.

6-bigint: Números enteros muy grandes.

7-symbol: Valores únicos usados como identificadores.

Estructuras de Control de Flujo
Sirven para decidir qué código ejecutar y cuántas veces.

1. Condicionales
Se usan para ejecutar bloques de código dependiendo de una condición.

if/else:
let edad = 20;
if (edad >= 18) {
  console.log("Mayor");
} else {
  console.log("Menor");
}

switch: Se usa cuando hay muchas condiciones posibles para un mismo valor.
let dia = 1;
switch (dia) {
  case 1:
    console.log("Lunes");
    break;
  case 2:
    console.log("Martes");
    break;
  default:
    console.log("Otro día");
}

2. Bucles
for: Ejecuta un bloque un número definido de veces.

for (let i = 1; i <= 3; i++) {
  console.log(i);
}

while: Se repite mientras la condición sea verdadera.

let i = 1;
while (i <= 3) {
  console.log(i);
  i++;
}

do...while: Ejecuta al menos una vez, aunque la condición sea falsa.

let j = 1;
do {
  console.log(j);
  j++;
} while (j <= 3);

🔠Importancia de usar nombres significativos para variables y métodos: Usar nombres significativos para variables y métodos en muy impórtate porque
permite que el código sea más claro, fácil de comprender y mantener tanto para uno como para los demás desarrolladores. Un nombre describe la función o el dato que
representa, lo que reduce errores y evita confusiones, facilitando así el trabajo y cumpliendo las buenas prácticas de programación. 

⚙️ Variables de Entorno
Son valores que se guardan en el sistema operativo y se usan para configurar el funcionamiento de programas. Permiten separar la configuración del código,
haciendo que las aplicaciones sean más seguras, portables y fáciles de mantener.

En Node.js, son de gran importancia porque permiten almacenar información sensible (claves de API, contraseñas, etc.) sin exponerla en el código fuente. 
También facilitan que una misma aplicación funcione en distintos entornos (desarrollo, pruebas o producción) sin modificar el código.

🛠️ Herramientas de Desarrollo de Chrome
Las Herramientas de Desarrollo de Chrome (DevTools) son un conjunto de utilidades para depuración y perfiles web integradas en el navegador Google Chrome.
Permiten a desarrolladores y diseñadores revisar errores, probar código, analizar el rendimiento y modificar una página en tiempo real.

Cómo acceder a las DevTools
.Clic derecho en la página y seleccionar "Inspeccionar".

Atajos de teclado: F12, Ctrl + Shift + I o Cmd + Option + J.

Paneles Principales
Panel Elements: Permite explorar la estructura HTML de la página y los estilos CSS aplicados. Puedes editar etiquetas, clases o estilos y ver los cambios al instante.

Panel Console: Funciona como una terminal dentro del navegador. Se puede escribir y ejecutar comandos de JavaScript, y muestra mensajes de depuración, advertencias y errores del sitio web.

Panel Network: Lista todos los recursos que carga la página (archivos CSS, JavaScript, imágenes, solicitudes de API, etc.). Muestra detalles como el tamaño, el tiempo de carga y los fallos, lo que ayuda a optimizar la velocidad y resolver problemas de conexión.
