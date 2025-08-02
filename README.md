# ONE: 
# Lógica en programación: Sumérgete en la programación con JavaScript
En este archivo podras acceder a mis aprendizajes y la aplicacion de ellos. Con el objetivo de realizar un juego básico de adivinación de un número secretro.
![caratula](https://github.com/user-attachments/assets/fef2f3ea-4747-49e8-8ce8-4d7457ae5e31)

**Herramientas**

- [Plataforma Alura Latam](https://www.aluracursos.com/promo/Aprendealuralatam20?utm_source=google&utm_medium=cpc&utm_campaign=AL_PRF_Search_Institucional&gad_source=1&gad_campaignid=22416289165&gclid=CjwKCAjw7rbEBhB5EiwA1V49nU4Vk0TT9bMwNV0RxcBZzwHaddCRCfljULr9kGeJxr3LSYD4g7BMsRoCgvwQAvD_BwE)  
- [ChatGPT](https://chatgpt.com)


      - Sumpergete en la programación con Js
        - Iniciando con JavaScript
        - Condicionales y concatenación
        - Loops y tentativas
        - Buenas practicas en programación
        - Desafío


### Iniciando con JavaScript

1. **¿Qué es la lógica de la programación?**

Es la capacidad de organizar y estructurar ideas para resolver problemas a través del código

<img width="738" height="572" alt="image" src="https://github.com/user-attachments/assets/726bd7ef-8a46-4f1b-8218-bb987ea3ae5f" />


Aprendemos la lógica en programación porque es la base del razonamiento computacional. Te enseña a pensar de manera clara, objetiva y estructurada.

Como por ejemplo, los pasos que uno tiene para abrochar un zapato: tomar los calcetines, tomar el par de zapatos, sentarte, ponerte un calcetín a la vez, poner los zapatos, ajustar y atar.

2. **¿Qué es un lenguaje de programación**

Las computadoras operan con impulsos eléctricos que se representan mediante código binario ( 0 y 1 ). Para comunicarnos con las máquinas utilizamos el lenguaje de programación.

Este lenguaje es un conjunto de palabras, símbolos y reglas que permiten escribir instrucciones para que la computadora pueda interpretar y ejecutar. 

Existe hasta un lengua de Emojis https://github.com/emojicode/emojicode

Errar es parte del proceso de aprender a programas. Debemos ser pro activos en investigar, buscar, leer, etc. Tomaremos un roll de detectives que buscan la solución ante el problema.

JavaScript es:

- El lenguaje mas popular y utilizado
- Funciona directamente en el navegador
- Permite ver el resultado del código casi en tiempo real
- Es una excelente puerta de entrada para el desarrollo web y para aprender lógica.

3. **Proyecto inicial**

Herramientas: Visual Studio Code 

4. **Preparando el ambiento**

Instalar VSCode.

A diferencia de otros lenguajes que necesitan programas específicos para ejecutarse, JavaScript funciona directamente en el navegador. Es decir, además de VS Code, no necesitas instalar nada para comenzar a probar tu código. Solo necesitas tener un navegador instalado — como Google Chrome, Firefox, Edge u Opera — y ya podrás ejecutar tus primeros scripts directamente en la pantalla.
**El proyecto base contiene:**

- Una carpeta con **imágenes** que se usarán en actividades futuras;
- Un archivo **HTML**, responsable de estructurar el sitio y conectar los otros archivos;
- Un archivo **CSS**, que define el estilo visual de la página (colores, fuentes, tamaños, etc.);
- Un archivo **JavaScript**, donde vamos a escribir nuestro código y ejercicios.

Aunque el proyecto trae varios archivos, en este momento nos enfocaremos solo en el archivo JavaScript, ya que es en él donde pondrás en práctica todo lo que estás aprendiendo sobre lógica de programación.

**Después de descargar el proyecto abriremos VSCode:**

- Ve al menú **Archivo > Abrir Carpeta** (o `File > Open Folder`, si el VS Code está en inglés).
- Pega la ruta de la carpeta copiada anteriormente.
- Haz clic en **Seleccionar Carpeta**.

**¿Cómo abrir el proyecto en el navegador?**

Lo que realizamos en el VSCode con código en JavaScript, lo hacemos del archivo index.html en el navegador.  Esto sucede porque el navegador necesita un **punto de entrada** para cargar toda la página, y ese punto es precisamente el HTML. El archivo HTML es el responsable de estructurar el contenido de la página e indicar al navegador qué archivos adicionales debe cargar, como:

- El **CSS**, que define el estilo (colores, fuentes, tamaños, etc.);
- El **JavaScript**, que define el comportamiento y la lógica de la aplicación.

Es decir, **es el HTML el que llama al JavaScript**, y por eso, es él que necesitamos abrir para ver el resultado de nuestro código funcionando en la práctica. Así que:

1. En **Visual Studio Code**, localiza el archivo `index.html` dentro de la carpeta del proyecto.

2. Haz clic derecho sobre él.

<img width="338" height="161" alt="image" src="https://github.com/user-attachments/assets/8603085b-06e9-4ade-91f7-61385f899601" />


3. Selecciona la opción **"Revelar en el Explorador de Archivos"** (o **"Reveal in File Explorer"**, si el VS Code está en inglés).

<img width="557" height="249" alt="image" src="https://github.com/user-attachments/assets/b49e0358-fe7e-41fd-adb8-a23b4f1292aa" />


4. La carpeta se abrirá en tu computadora. Ahora, **haz doble clic en el archivo `index.html`**. 

<img width="232" height="197" alt="image" src="https://github.com/user-attachments/assets/2daefe66-f8a9-4d9a-8558-4ff8f04fdaa1" />

5. ¡Listo! El navegador predeterminado de tu sistema se abrirá con el proyecto cargado. 

<img width="1413" height="622" alt="image" src="https://github.com/user-attachments/assets/30f08baf-4dad-4362-8c5f-a18056e26e17" />


Siempre guardar el archivo ante cualquier cambio (Ctrl + S)

Actualizar la pagina en el navegador (F5 o en recargar)

5. **Variable**
    1. Tenemos 3 archivos en el proyecto:
        1. index.html: Renderiza o construye la interface 
        2. style.css: Estilos, formas de la interfaz
        3. app.js: Es donde trabajaremos en este proyecto 
    
    El primer contacto es el tradicional “Hola Mundo” y se hace de la siguiente manera:
    
    En app.js debe poner: 
    
    ```jsx
    alert('Hola Mundo');
    ```
    
    <img width="616" height="175" alt="image" src="https://github.com/user-attachments/assets/61f263b5-8517-4e7e-9cd9-23dbc58cb941" />

    
    Las ‘’ es lo que queremos que se vea en el navegador (comillas simple o comillas dobles).
    
    el ; es necesario poner en cada uno de las sentencias 
    
    alert: es un mensaje de alerta o un pop -up (ventana emergente)
    
    Para integrar lo nuevo que estamos trabajando, es necesario vincular o agregar lo que tenemos en la pestaña de app.js al index.html. En este caso del proyecto, lo agregaremos al final del código de index.html. Pero existen diferentes casos donde es recomendable ubicarlos en ciertas líneas de código específicas como en la cabecera. 
    
    ```jsx
    <script src="app.js"></script>
    ```
    
    script:
    
    src: atributo, origen (source), donde tener el archivo
    
    <img width="757" height="757" alt="image" src="https://github.com/user-attachments/assets/eb1037ad-a56a-48a3-af63-8a920d8911ec" />

    

Para continuar con el proyecto debemos recordar que tenemos que automatizar el juego (adivinador de número) y para esto, necesitamos interacción con el usuario. Para esto tenemos el método prompt, la cual nos permite hacer preguntas al usuario, podemos enviar un mensaje para que el usuario complete la información solicitada. 

Cuando el usuario entrega el valor ¿Dónde va? A una variable (espacio en memoria, como un papel, caja que recibe datos) Para esto, debemos indicársela a JS y se hace con 3 palabras claves que van a definir el como se comportara esa caja que recibe datos. Estas son: const, let y var. En este caso vamos a utilizar “let” (mas adelante se estudiara estas variables).
Para poder llegar a esta caja, necesitamos saber como se llama, para esto a las variables hay que asignarles un nombres y una forma correcta de llamarlas es: 

- camel case (notación de camello): siempre escribirlas en minúscula y si la variable tiene más de una palabra, la primera letra de la segunda palabra y las palabras sucesivas siempre se coloca en mayúsculas. (let numeroUsuario) (numeroDeUsuario)
- RECORDAR: Utilizar nomenclaturas  representativo y auto explicativas

<img width="1006" height="142" alt="image" src="https://github.com/user-attachments/assets/cadfdfad-f293-4208-a341-393cf4ccc2f5" />


Explicación de la sintaxis: 

Cuando trabajamos con asignación o declaración de variables, la variable va al lado izquierdo. Vamos a encontrar el = (asignación), después al lado derecho encontraremos el valor que se le va atribuir. 

prompt: instrucción o pregunta, una ventana emergente (popup) al usurio, permite que le usuario escriba algún dato, devuelve el dato como un string

Variable creada: numeroUsuario

<img width="488" height="168" alt="image" src="https://github.com/user-attachments/assets/a29b3955-ce70-4543-9ca2-56ffba7c4120" />


<img width="487" height="212" alt="image" src="https://github.com/user-attachments/assets/66aef7d7-1c8f-41e6-8db2-7dc58079fed0" />


6. **Condición if**

Al construir nuestro prompt (Me indicas un número por favor) y definir nuestra variable (numeroUsuario), donde el usuario coloca el número, pero no sabemos donde queda almacenado esa respuesta (número), para esto verificamos en la consola del navegador.

<img width="726" height="100" alt="image" src="https://github.com/user-attachments/assets/07478603-7824-4010-9bc1-7d358b696683" />


Para unir esta información, debemos seguir trabajando en app.js y agregar el siguiente código

```jsx
console.log(numeroUsuario);
```

Esto va sin comillas porque estamos haciendo referencia a una variable, en nuestro caso, numeroUsurio. Colocamos las “” ‘ ‘ cuando es un valor constante, uno que no cambiara.

Al agregar este código, la información entregada por el usuario será almacenada en la variable numeroUsurio y se puede observar que sale el número consola del navegador.

Para continuar con el proyecto, vamos a crear otra caja, donde almacenaremos la respuesta correcta 

```jsx
let numeroSecreto = 6;
```

Esta respuesta será nombrada como variable numeroSecreto. Para comparar si el usuario apuesto la respuesta correcta (6) vamos a integrar la condición if

```jsx
if (numeroUsuario == numeroSecreto){ alert ('Acertaste el número');}
```

== : Comparar

RECORDAR: Los let  deben ir al inicio para mantener un orden

```
let numeroSecreto = 6;
let numeroUsuario = prompt("Me indicas un número por favor:");
console.log(numeroUsuario);
if (numeroUsuario == numeroSecreto){ alert('Acertaste el número');
}
```

<img width="461" height="146" alt="image" src="https://github.com/user-attachments/assets/1af1c9c5-079e-495b-9f71-311069e35595" />


7. **Alert y prompt**

<img width="925" height="973" alt="image" src="https://github.com/user-attachments/assets/6630694a-b32d-4189-bee3-ce570c5328d5" />


8. **Cambiando el valor de las variables**

<img width="927" height="716" alt="image" src="https://github.com/user-attachments/assets/7e7b1710-0e7e-4b33-99bc-da6d271d6bc5" />

9. **¿Dónde está el error?** 

<img width="686" height="925" alt="image" src="https://github.com/user-attachments/assets/6c5899fe-e4d4-4848-a6d9-332f893e4547" />


10. **Desafío: Hora de practicas**

Practicar la lógica de programación, incluyendo conceptos como variables, condicionales (if), alertas (alert), solicitudes (prompt), es esencial para tu carrera y desarrollo.

Estos fundamentos proporcionan la base para resolver problemas de manera estructurada, tomar decisiones en el código, crear bucles controlados e interactuar eficazmente con las personas.

Comprender estos conceptos no solo facilita el aprendizaje de nuevos lenguajes y tecnologías, sino que también te capacita para generar soluciones innovadoras, depurar de manera eficiente y mantener la calidad a lo largo del ciclo de vida del software.

Por lo tanto, invertir tiempo en estos principios desde el principio es fundamental para construir una carrera exitosa en el campo de la programación.

Con esto en mente, hemos creado una lista de actividades (no obligatorias) centradas en la práctica para mejorar aún más tu experiencia de aprendizaje. ¿Listo para practicar?

**Desafíos**

1. Muestra una alerta con el mensaje "¡Bienvenida y bienvenido a nuestro sitio web!".
    
    ```jsx
    alert("¡Bienvenida y bienvenido a nuestro sitio web!");
    ```
    
    <img width="457" height="142" alt="image" src="https://github.com/user-attachments/assets/66d671cc-8df6-41e4-bd85-8b5bfaa504ad" />

    
2. Declara una variable llamada nombre y asígnale el valor "Lua".
3. Crea una variable llamada `edad`y asígnale el valor 25.
    
    <img width="717" height="488" alt="image" src="https://github.com/user-attachments/assets/c8ea8d66-620d-42ad-9f5d-3bfeb917b785" />

    
    Nota: Al principio me arrojo error porque no use las “”, por ende JS interpreto Lua como variable y no texto.
    
4. Establece una variable numeroDeVentas y asígnale el valor 50.
5. Establece una variable saldoDisponible y asígnale el valor 1000.
    
    <img width="690" height="436" alt="image" src="https://github.com/user-attachments/assets/485fb8c0-1d73-4b07-8fa8-27adf8a89d35" />

    
6. Muestra una alerta con el texto "¡Error! Completa todos los campos".
    
    <img width="687" height="373" alt="image" src="https://github.com/user-attachments/assets/738452d6-f946-49bc-8fa3-4fd385eccea9" />

    
7. Declara una variable llamada mensajeDeError y asígnale el valor "¡Error! Completa todos los campos". Ahora muestra una alerta con el valor de la variable mensajeDeError .
    
   <img width="737" height="387" alt="image" src="https://github.com/user-attachments/assets/45671e5e-caac-4f5a-a547-38c8334b4489" />

    
8. Utiliza un prompt para preguntar el nombre del usuario y almacénalo en la variable nombre.
9. Pide al usuario que ingrese su edad usando un prompt y almacénala en la variable `edad`.

<img width="588" height="485" alt="image" src="https://github.com/user-attachments/assets/29fc67c5-21b5-4320-ac99-5aa7137ea0f9" />


<img width="383" height="166" alt="image" src="https://github.com/user-attachments/assets/b8f983a2-bedc-4fa5-9e32-9020dd874043" />


<img width="497" height="372" alt="image" src="https://github.com/user-attachments/assets/5ebe3102-8e56-4116-8321-c20cc3c845ee" />


10. Ahora, si la edad es mayor o igual a 18, muestra una alerta con el mensaje "¡Puedes obtener tu    licencia de conducir!"

<img width="607" height="297" alt="image" src="https://github.com/user-attachments/assets/089ab06d-2b22-4deb-9ba7-9dcd6e27b4a7" />


<img width="533" height="209" alt="image" src="https://github.com/user-attachments/assets/bc2c4bb8-396b-4459-afea-e1edc61755f4" />


<img width="536" height="142" alt="image" src="https://github.com/user-attachments/assets/791e1171-583a-4640-8ac1-28ae05dcd5a6" />


<img width="540" height="197" alt="image" src="https://github.com/user-attachments/assets/b3bcf9ee-5bf9-44dc-a96e-cc545338090b" />


<img width="532" height="133" alt="image" src="https://github.com/user-attachments/assets/47c04f07-cf9a-4d20-b8b8-342b994143b5" />


Explicación:

**`let edad = prompt("¿Cuál es tu edad?");`**

Pide al usuario su edad y la guarda en `edad` como texto.

**`edad = Number(edad);`**

Convierte el valor de `edad` de texto a número para poder compararlo.

**`if (edad >= 18) { alert(...) }`**

Usa una estructura de control `if` para verificar si `edad` es mayor o igual a 18.

Si es verdadero, muestra la alerta con el mensaje.

11. **Para saber más: documentación**
    1. https://www.aluracursos.com/blog/guia-de-javascript
        1. ¿Qué es JS?
            1. Lenguaje de programación 
            2. Destaca por dinamizar las páginas web
        2. ¿Dónde se ejecuta JS?
            1. El propósito principal es agregar interacción en las páginas
            2. Se ejecuta en los navegadores 
        3. Variables en JS
            1. Una variable es un espacio en la memoria de la computadora que reserva el programa en ejecución. Usamos este espacio para almacenar información, realizar operaciones, etc.
            2. Escopo / scope: Lugar donde una variable existe y se puede usar.
                1. Escopo global: La variable existe en todo el archivo o script, se puede usar en cualquier parte del código.
                2. Escopo local: La variable existe solo dentro de un bloque específico (una función {  }, un if, un for, etc). Fuera de ese bloque, no existe.
            3. Tiene 3 tipos de variables: 
                1. var: Evita usar en proyectos modernos.
                2. let: Se usa para variables que cambiarán de valor. Sus usos comunes son para contadores en “for”, varibles que cambian durante una función, estados intermedios.
                3. const: Se usa para valores que no deben cambiar. Su uso mas común es para constantes matemáticas, datos que no se deben modificar, referencias a objetos que no van a reasignarse
                    
                    <img width="557" height="163" alt="image" src="https://github.com/user-attachments/assets/1525412c-98ce-44f3-bb11-20c32ba00598" />

                    
            
            https://www.aluracursos.com/blog/tipado-dinamico-con-javascript
            
    2. https://developer.mozilla.org/es/docs/Learn_web_development/Core/Scripting/What_is_JavaScript
    
2. **Lo que aprendimos**

<img width="840" height="538" alt="image" src="https://github.com/user-attachments/assets/8496832c-e159-41c2-9dfa-08d633dc80fe" />


---

### Condicionales y concatenación

1. **Proyecto de aula anterior**
    1. Descargar una carpeta para trabajar
    
2. **Comentarios y Else**
    1. En JS podemos realizar comentarios en el código, ya sea para describir o dejar notas.
    2. Se utiliza: /* escribes el comentario */ o puede ser //escribe el comentario
    3. Else (*de otro modo*): Define una alternativa para ejecutar un bloque de código cuando la condición if no se cumple
        
        <img width="721" height="283" alt="image" src="https://github.com/user-attachments/assets/fbe20baa-21fe-4cc0-ac0a-39243c7a6f6f" />

        
        Como podemos observar, el comando ELSE nos esta dando la posibilidad de que el usuario este informado que su respuesta no es acorde a lo que el juego esta solicitando (6)
        
        RECORDAR: Estamos programando un juego para que el usuario adivine el número secreto.
        
3. **Template Strings**
    1. Técnica que permite la interpolación de variables (insertar valores dentro del texto)
    2. Se utiliza ` ` y ${    } 
        
        <img width="810" height="302" alt="image" src="https://github.com/user-attachments/assets/68759ca3-ce91-479a-81ac-12654e78b850" />

        
        Como vemos en el código, utilizamos las el acento al revés para tomar toda la línea de texto que vera el usuario, para luego solo poner ${ } en la variable que queremos que el usuario pueda visualizar. 
        
        <img width="232" height="77" alt="image" src="https://github.com/user-attachments/assets/4cc24a6d-13b8-4c0c-8a66-c03936cb9bfa" />

        
        Ejemplo mal ejecutado:
        
        <img width="777" height="262" alt="image" src="https://github.com/user-attachments/assets/71eb7b3f-8e28-4ca0-9b38-81ecfdd64742" />

        
        <img width="282" height="80" alt="image" src="https://github.com/user-attachments/assets/522a5ace-07e0-4401-8d03-79881eea3891" />

        
4.  **Live Server**
    1. Visual code, tiene una herramienta que se llama extensión, la cual ocuparemos Live Server, nos ayuda a ver de manera en directo como funciona nuestro código .
    
5. **Edad mínima para conducir**
    
    <img width="701" height="926" alt="image" src="https://github.com/user-attachments/assets/1e5f0795-2422-4195-aee1-d07b6d62bea0" />

    
6. **Cambiando el mensaje alert**
    
    <img width="697" height="937" alt="image" src="https://github.com/user-attachments/assets/9a66a920-f11f-4d72-b5f7-19e71420381b" />

    
7. **Trabajo con condicionales**
    
    <img width="692" height="826" alt="image" src="https://github.com/user-attachments/assets/67ca8692-b8b2-4024-b3bb-e38ed85d3488" />

    
8. **Haga lo que hicimos en aula: console.log**
    
    <img width="627" height="193" alt="image" src="https://github.com/user-attachments/assets/5da6193b-6d06-4de0-809f-a874abb640f2" />

    
9. **Desafío: hora de practicar**
    1. Pregunta al usuario qué día de la semana es. Si la respuesta es "Sábado" o "Domingo", muestra "¡Buen fin de semana!". De lo contrario, muestra "¡Buena semana!".
        
        <img width="671" height="225" alt="image" src="https://github.com/user-attachments/assets/b56297e7-d844-4d45-9344-40ec63889173" />

        
    2. Verifica si un número ingresado por el usuario es positivo o negativo. Muestra una alerta informativa.
        
        <img width="862" height="487" alt="image" src="https://github.com/user-attachments/assets/78008a6d-0743-413e-ada3-1321eda6adb3" />

        
        <img width="810" height="456" alt="image" src="https://github.com/user-attachments/assets/ae69e0de-95e4-4c2a-b03b-7288e549e8a6" />

        
    3. Crea un sistema de puntuación para un juego. Si la puntuación es mayor o igual a 100, muestra "¡Felicidades, has ganado!". En caso contrario, muestra "Intentalo nuevamente para ganar.".
    4. Crea un mensaje que informe al usuario sobre el saldo de su cuenta, utilizando un template string para incluir el valor del saldo.
    5. Pide al usuario que ingrese su nombre mediante un `prompt`. Luego, muestra una alerta de bienvenida usando ese nombre.
        
        <img width="702" height="400" alt="image" src="https://github.com/user-attachments/assets/b67dd978-9fba-4857-bd67-c941410737d0" />

        
10. **Para saber más: punto y coma en JavaScript**
    
    <img width="618" height="512" alt="image" src="https://github.com/user-attachments/assets/50a64c9c-2878-4c63-ada7-cbb1ca1b2ea4" />

    
    1. https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Lexical_grammar
    
11. **Lo que aprendimos**
    
    <img width="617" height="262" alt="image" src="https://github.com/user-attachments/assets/dda9bb89-f982-4031-acb5-2d91e666fbb1" />

    

---

### Loops y tentativas

1. **Proyecto del aula anterior**
    1. Se ha descargado 2034-logica-programacion-1-Aula2_practicaDelJuego
    
2. **Tips mayor o menor**
    
    <img width="811" height="410" alt="image" src="https://github.com/user-attachments/assets/04c3063f-3d6e-420c-bf30-e2c0377b9c46" />

    
    Hasta ahora, este es nuevo avance en el proyecto del juego. Pero necesitamos darle pistas al usuario para que pueda adivinar el número secreto. La idea es realizar una guía para poder encaminar la respuesta.
    
    Para aportar con la ayuda, realizaremos condiciones anidadas, la cual es una condición dentro de otra condición. 
    
    <img width="825" height="535" alt="image" src="https://github.com/user-attachments/assets/f609fc86-7494-4807-9164-eef7ba120b7d" />

    
3. **Loops y bucles**
    1. Con el punto anterior, pudimos dejar que el usuario pudiera jugar solo una vez, para que pueda volver a intentarlo sin tener que volver a recargar la página podemos agregar una acción para que lo intente otra vez. 
    2. Las claves son: Hasta, Mientras o Para. Por el momento vamos a ocupar la palabra mientras, en JS será el comando WHILE. Para ocupar esta condición, debemos encerrar nuestro código bajo el while con tabulación
        
        <img width="871" height="605" alt="image" src="https://github.com/user-attachments/assets/d901474b-31ee-4c71-88bd-25f02aec645b" />

        
        Con el WHILE estamos diciendo que mientras no se cumpla la condición, algo va a sucecer en ese código.
        ! = significa diferente de
        Pero tenemos un error, estamos declarando la variable dentro del repit y esto es un error. Para esto, tenemos que dejar la variable fuera del while . Sacamos la declaración de la variable. Siempre debemos declarar las variables antes de cualquier acción. 
        
        Terminado de acomodar las variables y ubicar bien los { }, el código quedaría de la siguiente manera 
        
        <img width="805" height="627" alt="image" src="https://github.com/user-attachments/assets/41af963a-4972-4dec-b37a-5365d53a2280" />

        
4. **Contador de intentos**
    1. Para que nuestro juego tenga un limite de intento, aplicaremos un contador. Para esto crearemos una variable llamada intentos, este contador podemos dejarlo dentro del WHILE  y le asignaremos un 1, ya que al menos tendrá 1 intento para iniciar en el juego. 
    2. Si al primer intento lo adivino el numero, necesita incrementar los intentos, para esto JS tiene 3 formas de hacer un contador, la primera es la variable intentos + un intento mas. 
    3. Para que el usuario pueda saber en cuantos intentos necesito para ganar, podemos completar  mas la alerta de acertaste para que muestre el número de intentos.
    4. Otro punto a tener en cuenta, es que si el usuario acierta a la primera, el mensaje que le saldrá tendrá un problema lingüístico, ya que no concuerda “1 veces”. Para esto vamos a agregar una variable para especificar cuando ocupar vez y  veces. Aprovechamos el alert para adjuntar ${ y agregar la variable nueva.
    5. Pero ahora nos surge otro problema, necesitamos especificar que diferencie entre vez y veces, para esto nos ubicamos en el contador y ahí ubicamos la sentencia para que que cuando lo realice en mas de 1 intentos, puede JS leer y deducir que la variable  palabraVeces puede cambiar al activar el contador de intentos. 
        
        <img width="1074" height="782" alt="image" src="https://github.com/user-attachments/assets/206e313a-6601-4670-b5c7-0dd57ed7e5e3" />

        
5. **Contador 1**
    
    <img width="617" height="936" alt="image" src="https://github.com/user-attachments/assets/21b5d49c-e19a-41bf-ade8-c4cc06b69682" />

    
6. **Bucle infinito**
    
    <img width="591" height="617" alt="image" src="https://github.com/user-attachments/assets/a358a2ea-c95b-449d-ac13-4221a7ab66ff" />

    
    <img width="610" height="762" alt="image" src="https://github.com/user-attachments/assets/26408e80-4ca5-46f5-836f-86c2b0fb4c14" />

    
7. **Desafío: Hora de practicar**
    
    Hemos llegado a otra lista de actividades (no obligatorias) para que practiques y refuerces aún más tu aprendizaje. ¿Vamos a hacerlo? 
    
    1. Crea un contador que comience en 1 y vaya hasta 10 usando un bucle 'while'. Muestra cada número.
      <img width="362" height="196" alt="image" src="https://github.com/user-attachments/assets/21e1b544-5b19-48b4-8949-41f96abc4717" />
      <img width="477" height="302" alt="image" src="https://github.com/user-attachments/assets/4f43d1ff-079f-4497-8248-a05631ef1cb7" />


    2. Crea un contador que comience en 10 y vaya hasta 0 usando un bucle 'while'. Muestra cada número.
      <img width="372" height="223" alt="image" src="https://github.com/user-attachments/assets/adf450ae-4e6b-491e-ae23-48db8bd0f433" />
      <img width="483" height="307" alt="image" src="https://github.com/user-attachments/assets/11298998-2b9c-42a6-a612-80da37606fdf" />
      RECORDATORIO: - - Se ocupa el doble menos (- -) para hacer decremento


    3. Crea un programa de cuenta progresiva. Pide un número y cuenta desde 0 hasta ese número utilizando un bucle 'while' en la consola del navegador.
      <img width="838" height="262" alt="image" src="https://github.com/user-attachments/assets/8d9d0aa8-4468-40a9-b42d-2a49e1fac643" />
      <img width="591" height="328" alt="image" src="https://github.com/user-attachments/assets/70a3282d-3c40-4f2c-b0f6-3d8769f75723" />


    5. Crea un programa de cuenta regresiva. Pide un número y cuenta desde 0 hasta ese número utilizando un bucle 'while' en la consola del navegador.
      <img width="856" height="227" alt="image" src="https://github.com/user-attachments/assets/1bea5fc2-0de2-4607-a67f-ce9370dd1821" />
      <img width="477" height="201" alt="image" src="https://github.com/user-attachments/assets/94c917a9-84f8-47c6-81a5-fa7bccb1ad61" />


    
8. **Para saber más: operadores lógicos**
    
    <img width="822" height="766" alt="image" src="https://github.com/user-attachments/assets/f3ea327e-020a-41ad-8ee1-ab23a9f01d17" />

    <img width="842" height="927" alt="image" src="https://github.com/user-attachments/assets/65bb49aa-4727-462b-b598-afa536375f56" />

    <img width="632" height="273" alt="image" src="https://github.com/user-attachments/assets/436a3bb9-e80c-433f-92c6-f450bdde2189" />

    
    https://www.aluracursos.com/blog/como-utilizar-operadores-de-comparacion-en-javascript
    
9. **Lo que aprendimos**
    
    <img width="836" height="301" alt="image" src="https://github.com/user-attachments/assets/3e1debf0-c075-43de-9fe5-9536c38cde7b" />

    

---

### Buenas prácticas en programación.

1. Proyecto anterior
    1. Descargar https://github.com/alura-es-cursos/2034-logica-programacion-1/tree/Aula3
2. Break
    1. Vamos a subir la dificultada en nuestro juego limitando los intentos, para esto aprenderemos un nuevo concepto llamado “la ruptura forzada” o “salir forzado” de un bucle.
    2. Agregamos una condición extra abajo del comando de los intentos, esta condición se realizara con IF, podemos también adjuntar una alerta donde le informe al usuario que ha llegado al limites de intentos. Al final de este IF, agregaremos el BREAK, esto le dará a entender a JS que al intentarlo x número de veces deberá romper el bucle.
        
        <img width="1057" height="860" alt="image" src="https://github.com/user-attachments/assets/7ff3150b-b0d0-4940-a9e7-4deced20d1d3" />

        
3. Solo 5 intentos
    
    <img width="621" height="937" alt="image" src="https://github.com/user-attachments/assets/421b3b83-d19b-4b4b-a16f-f930f6371b0d" />

    
4. Operador ternario
    1. Dejar condiciones con valores literales no es una buena práctica, ya que complica la mantenibilidad y el crecimiento de nuestro programa. Entonces, vamos a definir una variable llamada `maximosIntentos`. Por ahora, manteniendo la funcionalidad, le asignamos el valor de 3 y hacemos el cambio de que si los intentos del usuario son mayores que `maximosIntentos`.
    2. Realizaremos un cambio de optimización con un par de recursos, cambiaremos la forma de hacer el contador, existe una forma mas abreviada, pueden ser: intentos +=1; ó intentos++; Esto nos ayudara a reducir el código. Aquí lo que cambiamos fue el incrementados intentos.
    3. Nuestra segunda mejora será el “operador ternario”, al usar template strings dentro de nuestra frase “Acertaste, el número…” para usar las palabras en singular o plural en función de intentos, resumimos todo en una sola frase.  Lo que se esta haciendo en este cambio es que en la condición intentos == 1 ? le estamos diciendo que si el valor de la variable intentos es igual a uno es verdadero (ya que el usuario adivino con un solo intento), por ende debe mostrar en el mensaje “vez”, pero si es mas de un intento, esto deberá ser falso. ( : veces ) 
    == comparación
    ? si la condición es verdadera, usa lo de la izquierda de los dos puntos :
    : (simboliza else  ó si no )si la condición es falta, usa lo de la derecha
        
        <img width="1251" height="886" alt="image" src="https://github.com/user-attachments/assets/41822c02-20fc-4362-b4a0-e4c94f6bed60" />

        
        Un operador ternario es una forma corta de escribir una estructura if … else. Esta tiene su propia sintaxis:
        
        ```jsx
        condición ? valor_si_verdadero : valor_si_falso
        ```
        
5. **Refactorizando**
    
    <img width="818" height="893" alt="image" src="https://github.com/user-attachments/assets/35565ef9-f283-45ae-8812-9d604435256a" />

    
6. **Math.random () en nuestro código**
    1. https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Global_Objects/Math/random
    2. Lo que nos falta ahora en nuestro juego es que el número secreto sea aleatorio. La función Math. tiene una amplia funciones para trabajar, pero ahora ocuparemos Math.random.
    3. Por ejemplo, si ocuparemos Math.random la consola solo nos arrojara una infinidad de número random, pero podemos limitarlos con ( )*10, esto quiere decir, que limitaremos de 0 a 10 número. El problema aqui es que al no estar especificado, nos arrojara hasta los numero decimales ( 0.45, 2.487, 9.99, etc) Para esto ocuparemos las otras funciones que ofrece Math. 
    4. Al ocupar Math.floor(Math.random( ) estamos pidiendo que nos de un numero ENTERO (floor) aleatorio. Pero para ser aun mas específicos, podemos solicitar lo siguiente: Math.floor(Math.random( )*10); aquí estamos solicitando un número aleatorio entero del 0 al 9
    5. Para poder incluir el número 10 y excluir el 0, simplemente a Math.floor(Math.random( )*10) debemos agregar un +1 Math.floor(Math.random( )*10) +1;
        
        ![Esto se realizó en la consola de x página web]<img width="302" height="271" alt="image" src="https://github.com/user-attachments/assets/ecec7114-beba-422a-9578-e020b838c0e9" />

        
        Esto se realizó en la consola de x página web
        
7. **Número aleatorio**
    
    <img width="827" height="870" alt="image" src="https://github.com/user-attachments/assets/c70477d1-43aa-460a-ab08-acf9efeb130d" />

    
8. **Math.random ( ) en nuestro código**
    1. Hemos aplicado a nuestro código lo aprendido con Math.random, cambiando la variable numeroSecreto = 5 por lo aprendido y además para verificar nuestra escritura, agregamos un console.log para ir testeando.
        
        <img width="1272" height="877" alt="image" src="https://github.com/user-attachments/assets/20e05b9c-eff4-4b33-abab-f9f9b00ab405" />

        
        Para métodos de jugabilidad, borraremos el consolo.log(numeroSecreto);
        
    2. En el promt (”Me indicas un n…) nos retorna el número del usuario y es posible saber el tipo de dato con la funcionalidad llamada TYPEOF (Te dice de que tipo es un valor o variable)
        
        ¿Por que es importante usar TYPEOF?
        Porque evita errores de lógica, verifica qué tipo de dato te están devolviendo y depura el código.
        
        ```jsx
        typeof "hola"       // "string"
        typeof 42           // "number"
        typeof true         // "boolean"
        typeof undefined    // "undefined"
        typeof null         // "object" (esto es un detalle raro de JavaScript)
        typeof NaN          // "number"
        ```
        
    3. También podemos unas el PARSEINT (su función es convertir un texto (string) en número entero) Ejemplo:
        
        ```jsx
        parseInt("7"); // Devuelve el número 7
        parseInt("42"); // Devuelve el número 42
        parseInt("5.8"); // Devuelve el número 5 (solo la parte entera)
        parseInt("abc"); // Devuelve NaN (Not a Number, porque no puede convertir letras)
        ```
        
        ¿Por que es importante usar PARSEINT?
        Porque cuando trabajamos con `prompt`, siempre recibimos texto. Si queremos hacer comparaciones numéricas, sumas o cálculos, debemos asegurarnos de que el valor sea un número real, no texto.
        
        <img width="1240" height="867" alt="image" src="https://github.com/user-attachments/assets/93c618d8-1799-4000-b59b-5fbf4c859095" />

        
9. **Desafío: Hora de practicar**
    1. Crea un programa que utilice `console.log` para mostrar un mensaje de bienvenida.
    2. Crea una variable llamada "nombre" y asígnale tu nombre. Luego, utiliza `console.log` para mostrar el mensaje "¡Hola, [tu nombre]!" en la consola del navegador.
    3. Crea una variable llamada "nombre" y asígnale tu nombre. Luego, utiliza `alert` para mostrar el mensaje "¡Hola, [tu nombre]!".
        
        <img width="737" height="130" alt="image" src="https://github.com/user-attachments/assets/61934487-75aa-4600-8be6-e778b225198e" />
        <img width="1187" height="187" alt="image" src="https://github.com/user-attachments/assets/8ed1ae46-fc73-48a0-90b8-32a8aea8dda9" />

        
    4. Utiliza `prompt` y haz la siguiente pregunta: ¿Cuál es el lenguaje de programación que más te gusta?. Luego, almacena la respuesta en una variable y muestra la respuesta en la consola del navegador.
        
        <img width="862" height="97" alt="image" src="https://github.com/user-attachments/assets/b2f47b01-3ebc-4636-bb33-b86e59ab2853" />
        
        <img width="422" height="160" alt="image" src="https://github.com/user-attachments/assets/3a05576f-ed76-42e2-a7f2-bdd75d158f9d" />

        <img width="252" height="100" alt="image" src="https://github.com/user-attachments/assets/477061ee-2b28-4483-b8c8-5ea8af91494f" />

        
        RECORDAR: el signo + en JS (cuando se usa con cadena de texto) sirve para unir texto. Eso se llama CONCATENAR. Entonces en el ejemplo “Tu lenguaje favorito es: ” es un texto, mientras lenguajeDeProgramación es una variable que guarda lo que el usuario escribió. El + une ambos, para que se muestre todo junto. Para ahorrar problemas, recuerda usar los amados TEMPLATE   ` blablabla ${……….}`
        
    5. Crea una variable llamada "valor1" y otra llamada "valor2", asignándoles valores numéricos de tu elección. Luego, realiza la suma de estos dos valores y almacena el resultado en una tercera variable llamada "resultado". Utiliza `console.log` para mostrar el mensaje "La suma de [valor1] y [valor2] es igual a [resultado]." en la consola.
    6. Crea una variable llamada "valor1" y otra llamada "valor2", asignándoles valores numéricos de tu elección. Luego, realiza la resta de estos dos valores y almacena el resultado en una tercera variable llamada "resultado". Utiliza `console.log` para mostrar el mensaje "La diferencia entre [valor1] y [valor2] es igual a [resultado]." en la consola.
        
        <img width="675" height="257" alt="image" src="https://github.com/user-attachments/assets/794bd2f8-2bd9-4810-9f14-693f8994aa29" />
        
        <img width="478" height="122" alt="image" src="https://github.com/user-attachments/assets/a3f7f968-f274-485a-93c5-d12058fd82bf" />

        
    7. Pide al usuario que ingrese su edad con `prompt`. Con base en la edad ingresada, utiliza un `if` para verificar si la persona es mayor o menor de edad y muestra un mensaje apropiado en la consola.
    8. Crea una variable "numero" y solicita un valor con `prompt`. Luego, verifica si es positivo, negativo o cero utilizando un `if-else` y muestra el mensaje correspondiente.
        
        <img width="667" height="185" alt="image" src="https://github.com/user-attachments/assets/749d8dd0-4d5d-492d-9ffd-ce164cae0f47" />

        <img width="252" height="112" alt="image" src="https://github.com/user-attachments/assets/576e35ba-cc13-4108-a4c3-c7a1e3c8199a" />

        <img width="232" height="107" alt="image" src="https://github.com/user-attachments/assets/fda27368-e19a-42f7-9a4e-75447c6c0530" />

        
    9. Utiliza un bucle `while` para mostrar los números del 1 al 10 en la consola.
        
        <img width="325" height="181" alt="image" src="https://github.com/user-attachments/assets/0b35dbee-1dd2-4b7d-afdb-b7116ab44f49" />

        <img width="465" height="297" alt="image" src="https://github.com/user-attachments/assets/92022084-187b-409d-ac87-55e45b93f982" />

        
        RECORDAR: 
        
        Los paréntesis llave {  } definen bloques de códigos (forman la caja), es decir, ayuda a agrupar el conjunto de instrucciones que se ejecutan si la condición (caja) se cumple.
        
        El ++ es un operador de incremento, ósea decir: contador = contador +1 es lo mismo que decir contador++, pero el ultimo ejemplo es una buena practica a utilizar.
        
    10. Crea una variable "nota" y asígnale un valor numérico. Utiliza un `if-else` para determinar si la nota es mayor o igual a 7 y muestra "Aprobado" o "Reprobado" en la consola.
        
        <img width="526" height="240" alt="image" src="https://github.com/user-attachments/assets/9831764e-9291-44cb-8574-8e3a840d1360" />

        
    11. Utiliza `Math.random` para generar cualquier número aleatorio y muestra ese número en la consola.
    12. Utiliza `Math.random` para generar un número entero entre 1 y 10 y muestra ese número en la consola.
    13. Utiliza `Math.random` para generar un número entero entre 1 y 1000 y muestra ese número en la consola.
        
        <img width="265" height="485" alt="image" src="https://github.com/user-attachments/assets/2dcdc9f5-4454-4072-b108-b85059df1c49" />

        
10. **Para saber más: ¿Necesito memorizar cada línea de código o comando?**
    
    <img width="780" height="977" alt="image" src="https://github.com/user-attachments/assets/0facffea-e227-492b-b49c-94b1a12e7d25" />

    
11. **Lo que aprendimos** 
    
    <img width="737" height="243" alt="image" src="https://github.com/user-attachments/assets/1ebd03bf-5bf8-4ee9-b9ad-f11e2ec6f694" />

    

---

### Desafío

1. P**royecto de aula anterio**r
    1. Descargar proyecto: https://github.com/alura-es-cursos/2034-logica-programacion-1/tree/Aula4
2. **Desafío**
    1. Implementa nuevas funciones en tu código 
    2. Una de las funciones que siento que falta en el juego, es seleccionar la dificultad. Dividir el juego por niveles, se puede abrir ventanas para diversidad de jugadores, desde edades mas pequeñas, nivel de tolerancia para cada usuario o simplemente ir subiendo o bajando la dificultada según lo requiera el usuario.  Para esto investigue si existe la posibilidad de hacerlo y encontré una abanico de herramientas que me pueden ayudar a plasmar mi idea. Estas son:
        1. swith: Estructura de control, es como if, pero me permite comparar una misma variable contra varios valores posibles (casos). Se utiliza para simplificar múltiples comparaciones cuando una misma variables puede tener varios valores distintos.
            
            La ocuparemos para entregarle a nuestro juego los niveles de dificultades (fácil, medio y difícil) 
            
        2. case: Define una posible opción o valor dentro de un switch. Cuando usamos switch, estamos revisando una sola variable para ver cuál case coincide. Se utiliza cunado estamos evaluando una misma variable con varias opciones posibles. El case se usa solo cuando ocupamos switch
            
            Con case, crearemos los niveles de dificultad y le pondremos un límites de posibles números secretos y un limite de intentos. También en cada case, cerraremos con un break para romper el bucle 
            
        3. toLowerCase: es un método  que aplica a cadenas de testo (string) y convierte todas las letras en minúsculas. Se utiliza para evitar errores por mayúsculas o minúsculas cuando comparas texto. 
            
            En nuestro juego, ocuparemos este método para que el usuario pueda escribir su nivel de dificultad. JS es muy sensible a los string con mayúsculas y minúsculas, entonces al usarlo en nuestro código, nos ahorramos errores por tipeo (FACÍL, Fácil, fAcíl, etc)
            
        4. Para terminar de limitar bien los limites de cada nivel, crearemos una variable llamada limiteSuperior, esta variable nos ayudara a poner a trazar el limite de las dificultades para cada elección realizada por el usuario y esta la adjuntaremos dentro de la la caja de case según la dificultades con sus máximos límites de intentos. Realizado esto, debemos tener presente en cambiar la variable Math.random ( ) *10 a :(Math.random()*limiteSuperior) + 1;
    3. Por otro parte, leyendo algunos pdf, encontré una función llamada isNaN(¿esto NO es un número?). Esta función retorna true si el valor NO es un número y se utiliza para evitar errores y validar entradas.
        1. En nuestro juego usamos esta función porque estamos usando un prompt para pedirle al usuario un número, pero prompt( ) siempre devuelve un texto (string), luego usamos parseInt(…) para convertirlo a número, entonces si el usuario escribe algo que no es un número válido, parseInt () devuelve NaN y es aquí donde entra en juego isNaN( ). Por ejemplo, si seleccionamos dificultad fácil, debemos escribir un numero entre 1 a 50, pero en el caso de escribir 55, nos aparecerá un mensaje que nos indicara que ingresar un número válido entre 1 y 50.
    4. Otra herramienta a utilizar es continue, esta es una palabra clave que se utiliza dentro de bucle (while, for, do…). Se utiliza en ciertos casos como para ignorar entradas invalidas, saltar iteraciones innecesarias y filtrar cierto valores
        1. En el juego utilizamos esta herramienta para evitar que cuente como intento una entrada inválida. Por ejemplo, si el usuario en ves de escribir un número solicitado según la dificultad (-5 o perro), el juego no ejecutara el resto del código, pero si volvera a realizar la pregunta para que ingrese un número válido. 
    5. Para finalizar, para darle un toque mas llamativos, al principio del curso, se comentó que existía un lenguaje de emojis y se aprovecho la virtud de JS para agregarlos al código.
        1. Podemos usar los emojis en las alerts, console.log, prompt, cadenas de texto normales (”” ‘ ‘ ) e intefaces de HTML
    
    ```jsx
    // Elegir dificultad
    let dificultad = prompt("Elige dificultad: fácil, medio o difícil").toLowerCase();
    let limiteSuperior;
    let maximosIntentos;
    
    switch (dificultad) {
        case "fácil":
            limiteSuperior = 50;
            maximosIntentos = 10;
            break;
        case "medio":
            limiteSuperior = 100;
            maximosIntentos = 7;
            break;
        case "difícil":
            limiteSuperior = 500;
            maximosIntentos = 5;
            break;
        default:
            alert("Dificultad no válida. Se asignará dificultad media.");
            limiteSuperior = 100;
            maximosIntentos = 7;
        console.log(limiteSuperior);
    }
    
    // Variables principales
    let numeroSecreto = Math.floor(Math.random() * limiteSuperior) + 1;
    let numeroUsuario = 0;
    let intentos = 1;
    
    console.log("Número secreto:", numeroSecreto);
    
    while (numeroUsuario != numeroSecreto) {
        numeroUsuario = parseInt(prompt(`Indica un número entre 1 y ${limiteSuperior}:`));
    
        // Validación
        if (isNaN(numeroUsuario) || numeroUsuario < 1 || numeroUsuario > limiteSuperior) {
            alert(`Por favor, ingresa un número válido entre 1 y ${limiteSuperior}.`);
            continue;
        }
    
        console.log(typeof numeroUsuario);
    
        if (numeroUsuario == numeroSecreto) {
            alert(`🎉 Acertaste, el número es: ${numeroUsuario}. Lo hiciste en ${intentos} ${intentos == 1 ? 'vez' : 'veces'}.`);
        } else {
            if (numeroUsuario > numeroSecreto) {
                alert('📉 El número secreto es menor');
            } else {
                alert('📈 El número secreto es mayor');
            }
    
            intentos++;
    
            if (intentos > maximosIntentos) {
                alert(`❌ Has llegado al máximo de ${maximosIntentos} intentos. El número era: ${numeroSecreto}.`);
                break;
            }
        }
    }
    ```
    
    <img width="893" height="645" alt="image" src="https://github.com/user-attachments/assets/bdf35f88-9c17-4f4c-a2d0-33446f46f84a" />

    <img width="1301" height="862" alt="image" src="https://github.com/user-attachments/assets/75378c5f-e26c-43b4-b35a-b1e9a3e66692" />

    
3. **Solución del desafío**
    
    <img width="1232" height="867" alt="image" src="https://github.com/user-attachments/assets/a509067e-b5e8-4f6e-9588-efb182ecfbda" />

    
    1. Observando el código original (propuesta por las clases de one) podemos observar que tenemos un par de sitios donde no tenemos variables y ahora cambiaremos esos sitios. 
    2. Crearemos una variable para definir los limites entre x número, en este caso sera: numeroMaximoPosible = 10 (10 para mantener la funcionalidad del juego). Debido a esta creación de variable, iremos reemplazando el Math.ranbom( )*10 por numeroMaximoPosible
        
        <img width="1245" height="886" alt="image" src="https://github.com/user-attachments/assets/405ad4fc-1964-4554-80e5-e11790574724" />

        
4. **Lo que aprendimos**
    
    <img width="742" height="423" alt="image" src="https://github.com/user-attachments/assets/461d3379-7263-4a2a-bf98-7156ceb49281" />

    
5. **Proyecto final**
    1. Podemos descarga el proyecto final: https://github.com/alura-es-cursos/2034-logica-programacion-1/tree/Aula5
       
6. **Conclusión**
    1. Llevamos un simple juego de adivinanza numérica a un código ejecutable, donde aplicamos los conceptos y curiosidades en este código

---

<img width="658" height="467" alt="image" src="https://github.com/user-attachments/assets/f9da50b5-4393-426a-8cb8-f4e0d8c85e32" />
