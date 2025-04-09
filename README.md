
# Índice

- [GitHub](#GitHub)
- [MarkDown](#MarkDown)
- [HTML](#HTML)
- [CSS](#CSS)
- [Fontawesome](#Fontawesome)
- [Bootstrap](#Bootstrap)



# GitHub

GitHub es una plataforma donde puedes almacenar, compartir y trabajar junto con otros usuarios para escribir código.


Almacenar tu código en un "repositorio" en GitHub te permite:


* __Presentar o compartir__ el trabajo.
* __Seguir y administrar__ los cambios en el código a lo largo del tiempo.
* Dejar que otros usuarios __revisen__ el código y realicen sugerencias para mejorarlo.
* __Colaborar__ en un proyecto compartido, sin preocuparse de que los cambios afectarán al trabajo de los colaboradores antes de que esté listo para integrarlos.

[Ir a la pagina oficial](https://github.com/ "Es un link que te redirige a la pagina oficial de GitHub")


## Creacion de repositorios en GitHub

1. Para poder realizar la creación deberemos de seguir los pasos siguientes: 

    + Vaya a https://github.com/
    + Haga clic en Registrarse.
    + Sigue las indicaciones para crear tu cuenta personal.

    
2. Una vez te registres y logres acceder a tu cuenta, lograrás ver una pagina inicial y debererás de diriguirte a la parte arriba-derecha de la pantalla y clicar en tu perfil.

![Imagen pagina inicial](https://github.com/Nahuel-00/Dossier_GitHub_MarkDown_HTML/blob/main/img_github/imagen_inicial.png "esta es la primera imagen de GitHub")


3. Después de realizar lo anterior entraremos a un desplegable que nos permitirá poder diriguirnos a los repositorios.

![Ir a repositorios](https://github.com/Nahuel-00/Dossier_GitHub_MarkDown_HTML/blob/main/img_github/lista_opciones.png "Esto es una lista en la cual se encuentra unas opciones para ir a los repositorios")


4. Aqui podemos ver la barra de navegación para realizar el desplazamiento y deberemos de clicar en una barra en la cual tendremos unas opciones, deberemos de clicar en **Nuevo**.

![navbar](https://github.com/Nahuel-00/Dossier_GitHub_MarkDown_HTML/blob/main/img_github/barra.png "Aqui se pueden crear nuevos repositorios")

    
5.  Al clicar en **Nuevo** nos dirigiremos al lugar en el cual podremos configurar el repositorio, primero deberemos de introducir el nombre el cual no debe de tener espacios o acentos y sucesivamente que no es obligatrio pero es recomendado colocar la breve descripcion que nos servirá para poder identificar repositorios con nombre o contenido similar.

![creacion1](https://github.com/Nahuel-00/Dossier_GitHub_MarkDown_HTML/blob/main/img_github/creacion1_repositorio.png "Primera parte de la creacion del repositorio")

6. Luego, en la siguiente parte de la configuración de el repositorio tendremos que indicar si queremos que sea __publico__ (Lo pueden ver todas las personas) o __privado__ (Solo el creador lo puede ver), si queremos activar el GitHub pages para poder publicar el repositorio deberá ser publico. Deberemos de marcar la opcion del __README__ para que el repositorio se cree y se inicialice automaticamente.

![creacion2](https://github.com/Nahuel-00/Dossier_GitHub_MarkDown_HTML/blob/main/img_github/creacion2_repositorio.png "segunda parte de la creacion del repositorio")


7. Podremos observar que al clicar en __Crear repositorio__ en la parte final de la configuracion, al realizar esta accion autmaticamente creará el repositorio el cual ya estará listo para añadir contenido. Podremos ver los repositorios creados en la apartado de repositorios accediendo como antes lo he realizado.


![Repositorios](https://github.com/Nahuel-00/Dossier_GitHub_MarkDown_HTML/blob/main/img_github/repos.png "visualizacion de repositorios ya creados")



[//]: <> (aplicacion de git en Github)

## Acerca de Git
    
Git es un sistema de control de versiones que realiza un seguimiento de los cambios en los archivos. 

[Descargar Git](https://git-scm.com "Es un link que te redirige a la pagina oficial para descargar Git")

* Crear una rama a partir de la copia principal de archivos en los que tú (y tus colaboradores) estáis trabajando.
* Realizar modificaciones en los archivos de forma independiente y segura en tu propia rama personal.
* Dejar que Git realice un seguimiento de tus cambios y los de otras personas, por lo que todos siguen trabajando en la versión más actualizada del proyecto.


[//]: <> (aplicacion de git en cmd)

## Aplicación de Git desde CMD

| Orden| Descripción |
|:------------------|:-------------------:|
| ```git init``` | Si no hemos inicializado el repositorio, lo inicia y si ya lo hemos realizado, se reinicia.   |
| ```git branch```  | Se utiliza para mostrar la rama de main. |
| ```git add README.md```   | Los cambios que se han realizado en ese archivo especifico se suben a una zona intermedia.  |
| ```git add .```  | Se sube a la zona intermedia todos los archivos modificados dentro del directorio. |
| ```git commit -m "Ejemplo de comentario"```  | Se utiliza para poder realizar un commit despues de haber subido los cambios a la zona intermedia. |
| ```git push origin main```  | Realiza una subida del commit anteriormente grabado. |
| ```git pull```  | Se utiliza para poder sincronizar los cambios de un archivo en la nube cuando ya se ha cambiado el codigo abajo tambien. |



- [Volver al inicio](#índice)

# MarkDown

Markdown nació como herramienta de conversión de texto plano a HTML.
Aunque en realidad Markdown también se considera un lenguaje que tiene la finalidad de permitir crear contenido de una manera sencilla de escribir, y que en todo momento mantenga un diseño legible, así que para simplificar puedes considerar Markdown como un método de escritura.


[//]: <> (Explicacion de como utilizar los diferentes niveles de markdown)

## Formatos de encabezados

Aqui podemos ver los diferentes niveles de tamaños de encabezados que nos permite utilizar MarkDown podemos utilizar desde 1 almoadilla (#) hasta 6, donde 1 es la más grande y 6 la más pequeña.

```
# Primer nivel de encabezados
## Segundo nivel de encabezados
### Tercero nivel de encabezados
#### Cuarto nivel de encabezados
##### Quinto nivel de encabezados
###### Sexto nivel de encabezados
```



## Colocacion de negrita/resaltado de palabras

[//]: <> (Colocacion de negrita en los parrafos)


Para poder lograr que una palabra se vuelva negrita tendemos que añadirle dos barras bajas al principio y al final (_) ```__Ejemplo__``` otro metodo que tambien nos permite lograr el mismo resultado es añadiendo dos asteriscos (*) al principio y al final de la palabra ```**Ejemplo**```.

```

Estos son mis __apuntes__ del *0373* del ciclo de _ASIX_ / DAW del curso **2425**.

Las etiquetas en **_markdown_** y HTML pueden unirse.

```

### Resultado:

Estos son mis __apuntes__ del *0373* del ciclo de _ASIX_ / DAW del curso **2425**.

Las etiquetas en **_markdown_** y HTML pueden unirse.




## Listas ordenadas

estas listas son ideales para cosas que necesitan un orden secuencial, como una receta de cocina o pasos a seguir en un tutorial. Usas números para indicar la secuencia.

```

1. Primer punto de la lista
    1. primer elemento de la sudlista 1
    2. Segundo elemento de la sublista 1
2. Segundo punto de la lista
    * primer elemento de la sublista 2
    * Segundo elemento de la sublista 2

```

### Resultado:

1. Primer punto de la lista
    1. primer elemento de la sudlista 1
    2. Segundo elemento de la sublista 1
2. Segundo punto de la lista
    * primer elemento de la sublista 2
    * Segundo elemento de la sublista 2



## Listas desordenada


son útiles cuando no importa el orden de los elementos. Un ejemplo son los **Puntos destacados:** Para resaltar ideas clave.

```
1. Tercer punto de la lista

* Primer punto de lista desordenada
- Segundo punto de lista desordenada
+ Tercer punto de lista desordenada
```

### Resultado:

3. Tercer punto de la lista

* Primer punto de lista desordenada
- Segundo punto de lista desordenada
+ Tercer punto de lista desordenada




## Como mostrar código en un repositorio

Para poder mostrar nesecidad de que lo interprete como una intruccion deberemos de colocar el acento abierto (`) tres de cada lado de la etiqueta o de la palabra.

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Documento</title>

</head>
<body>

</body>
</html>
```

## Como poner un link

Un link nos sirve para poder realizar un salto desde la pagina web en que estamos a otra web que tenga contenido relacionado con el texto que se vuelve el enlace.

```
[textoClicable](URL "Titulo opcional")

```
### Resultado:

[Página web de jesuïtes Bellvitge](https://www.fje.edu/ca/jesuites-bellvitge/lescola "Titulo Opcional")


## Como poner una imagen

Colocar imágenes enriquecen y mejoran la comprensión de el proyecto que estamos realizando proyecto.


![Imagen de Venom](https://github.com/Nahuel-00/Dossier_GitHub_MarkDown_HTML/blob/main/img_markdown/venom.png "Titulo opcional")


## Creación de tablas

Las tablas te ayudan a presentar información de forma clara y accesible.

```
| Titulo 1| Titulo 2 | Titulo 3 |
|-------------|:---------:|---------:|
| SMX2     | Curso 2324   | 25  |
| **ASIX1**     | Curso 2425   | 33 |
| DAW2     | Curso 2425   | 32 |
```
### Resultado:

| Titulo 1| Titulo 2 | Titulo 3 |
|-------------|:---------:|---------:|
| SMX2     | Curso 2324   | 25  |
| **ASIX1**     | Curso 2425   | 33 |
| DAW2     | Curso 2425   | 32 |




## Colocación de comentarios en MarkDown

Colocar un comentario hace que el codigo para el desarrollador sea mas comprensible y facil ubicar un fallo o simplemente para recordar que hace cada linea.

```
[//]: <> (Ejemplo de como introducir un comentario en MarkDown)
```

- [Volver al inicio](#índice)

# HTML

Es básicamente el lenguaje que usamos para crear y estructurar páginas web. Se utilizan etiquetas para definir cosas como títulos, párrafos, enlaces, imágenes, etc. Esencialmente, HTML nos permite armar el contenido que ves cuando navegas por Internet, diciéndole al navegador cómo debe mostrar cada parte de la página.


## Organización de los archivos en una aplicación web

Recomendaciones para mantener una estructura organizada con un directorio principal y subdirectorios para diferentes tipos de archivos, nombrando el archivo principal como __index.html__.

## Comentarios en HTML
Los comentarios que no se muestran en el navegador,son útiles para los desarrolladores ya que te permite organizar y definir mejor las cosas para una mejor gestion del código. Ejemplo de colocación de comentario:

```<!-- Este es un comentario -->```


## Etiquetas anticuadas (deprecated) en HTML

En HTML, existen etiquetas que, aunque permitidas, deben evitarse porque se relacionan con la presentación del documento en lugar de su estructura. Ejemplos: ```<b>```, ```<i>```, ```<u>```, ```<font>```, ```<center>```. Además, se recomienda evitar atributos como align y border que pueden reemplazarse con CSS.



## Creación de enlaces y anclas en HTML

Para navegar dentro de un mismo documento HTML extenso:
* Crear una ancla: ```<h2 id="seccion1">Sección 1</h2>```
* Enlazar a la ancla: ```<a href="#seccion1" title="Sección 1">Ir a la sección 1</a>```
* Enlazar desde otro documento: ```<a href="secciones.html#seccion1" title="Sección 1">Ir a la sección 1</a>```


## Etiquetas básicas en HTML

Estas etiquetas nos sirven para construir y organizar contenido en una página web. Cada etiqueta tiene un propósito específico, como definir encabezados, párrafos,etc.

* Encabezados: ```<h1>...<h6>```
* Párrafos: ```<p>```
* Salto de línea: ```<br>```
* Separador de línea: ```<hr>```
* Énfasis: ```<em>```, ```<strong>```
* Span: ```<span>```


## Listas en HTML

### Listas no ordenadas

Las listas no ordenadas se crean con la etiqueta ```<ul>```. Pueden tener diferentes símbolos:

* Círculo relleno: ```<ul type="disc">```
* Cuadrado relleno: ```<ul type="square">```
* Círculo vacío: ```<ul type="circle">```



### Listas ordenadas

Las listas ordenadas se crean con la etiqueta ```<ol>``` y pueden usar varios tipos de numeración:

* Letras mayúsculas: ```<ol type="A">```
* Letras minúsculas: ```<ol type="a">```
* Números romanos mayúsculos: ```<ol type="I">```
* Números romanos minúsculos: ```<ol type="i">```
* Números: ```<ol type="1">```


## Validador de HTML

Este validador comprueba la validez de los documentos web en HTML,CSS, etc. Sirve para poder encontrar enlaces rotos o simplemente para verificar si nuestro codigo es correcto. Existen 3 formas para poder validar los archivos:

1. Utilizando la URL de nuestra página.
2. Subiendo directamente el archivo que contiene la página.
3. Copiando y pegando el codigo de la página en el validador.

![imagen validador](https://github.com/Nahuel-00/Dossier_GitHub_MarkDown_HTML/blob/main/img_html/validador.png "esta es la pagina web del validador")


[Ir al validador](https://validator.w3.org/ "Es un link que te redirige a la pagina para que puedas comprobar tus paginas web")




## Formularios en HTML

Los formularios en HTML permiten a los usuarios introducir información para que sea procesada por una aplicación web. Son esenciales para recopilar datos y enviarlos al servidor.

### ¿Qué es un formulario?

Un formulario es un bloque de código HTML formado por controles de entrada o campos, como pueden ser:

1. Campos de texto
2. Contraseñas
3. Botones de opción (radio)
4. Casillas de verificación (checkbox)
5. Menús desplegables (select)
6. Áreas de texto (textarea)
7. Carga de archivos
8. Botones

### Propiedades de un formulario

Para crear un formulario usamos la etiqueta ```<form>```. Sus atributos más importantes son:

* action: URL donde se enviarán los datos.
* method: cómo se enviarán los datos (get o post).


```
<form action="procesar.php" method="get">
  <!-- Aquí irán los campos -->
</form>
```

### Campo de texto

Se usa para que el usuario introduzca texto libre. Ejemplo: tu nombre.

```
<input type="text" name="nombre" id="nombre" />
```

![imagen campo texto](https://github.com/Nahuel-00/Dossier_GitHub_MarkDown_HTML/blob/main/img_html/campo_de_texto.png "esta es la imagen que representa el campo de texto")


### Campo de contraseña

A diferencia del campo de texto normal, los caracteres escritos no se muestran en pantalla, sino que aparecen como puntos o asteriscos

```
<input type="password" name="clave" id="clave" />
```
![imagen campo contraseña](https://github.com/Nahuel-00/Dossier_GitHub_MarkDown_HTML/blob/main/img_html/campo_de_contase%C3%B1a.png "esta es la imagen que representa el campo de introducir una contraseña")

### Botones de opción (radio)

Permiten escoger una sola opción entre varias.

```
<fieldset>
    <legend>Idioma:</legend>

        <input type="radio" id="cast" name="idioma" value="Castellano">
        <label for="cast">Castellano:</label>
            
        <input type="radio" id="cata" name="idioma" value="Catalan">
        <label for="cata">Catalan:</label>
            
        <input type="radio" id="chino" name="idioma" value="Chino">
        <label for="chino">Chino:</label>

</fieldset>
```

![imagen campo de radio](https://github.com/Nahuel-00/Dossier_GitHub_MarkDown_HTML/blob/main/img_html/radi.png "esta es la imagen que representa el campo de seleccionar una sola opcion")

### Casillas de verificación (checkbox)

Permiten marcar una o varias opciones.

```
<fieldset>
    <legend>Nacionalidad</legend>

        <input type="checkbox" id="nacionalidad" name="Española" value="espanola">
        <label for="espanola">Española</label>
            
        <input type="checkbox" id="nacionalidad" name="Frances" value="Freacesa">
        <label for="cata">Francesa</label>
            
        <input type="checkbox" id="nacionalidad" name="canadience" value="canadiense">
        <label for="chino">canadience</label>

</fieldset>
```

![imagen de checkbox](https://github.com/Nahuel-00/Dossier_GitHub_MarkDown_HTML/blob/main/img_html/checkbox.png "esta es la imagen que representa el campo de seleccionar varias opciones")

### Menú desplegable (select)

Muestra una lista de opciones para elegir.

```
<label for="ciudad">Ciudad</label><br>
    <select name="ciudad" id="ciudad">
        <option value="" selected>seleccione una ciudad</option>
        <option value="londres">londres</option>
        <option value="barcelona">barcelona</option>
        <option value="madrid" disabled>Madrid</option>
        <option value="valencia">Valencia</option>
    </select>
```

![imagen de un menú desplegable](https://github.com/Nahuel-00/Dossier_GitHub_MarkDown_HTML/blob/main/img_html/menu.png "Muestra una lista de opciones para elegir")

### Área de texto (textarea)

Sirve para escribir comentarios o textos largos.

```
<label for="observaciones">observaciones</label><br>
<textarea name="observaciones" id="observaciones" cols="80" rows="4" placeholder="introduce tus comentarios"></textarea>
```

![imagen de textarea](https://github.com/Nahuel-00/Dossier_GitHub_MarkDown_HTML/blob/main/img_html/textarea.png "imagen representativa del textarea")

### Botón


Sirve para enviar el formulario.

```
<button type="submit">Enviar datos</button>
```

![imagen de botón de envio](https://github.com/Nahuel-00/Dossier_GitHub_MarkDown_HTML/blob/main/img_html/boton.png "esta es la imagen de un boton que permite enviar el formulario")

### Métodos de envio de formularios

Cuando un usuario completa un formulario en una página web, los datos introducidos deben enviarse al servidor para que este los procese. Esto se hace a través de un formulario HTML, usando uno de estos dos métodos principales.


#### Método GET

Envía los datos como parte de la URL. Es útil para búsquedas o consultas simples.

```
<form action="recepcion.php" method="GET">

    <label for="nombre">Nombre:</label>
    <input type="text" id="nombre" name="nombre" placeholder="introduce tu nombre"><br><br>

</form>
```

#### Método POST

Envía los datos de manera más segura dentro de la petición HTTP. Es más seguro para enviar información como contraseñas o archivos.

```
<form action="recepcion.php" method="post">

    <label for="nombre">Nombre:</label>
    <input type="text" id="nombre" name="nombre" placeholder="introduce tu nombre"><br><br>

</form>
```






## HTML semántico

Es una forma de escribir HTML usando etiquetas que tienen significado. Estas etiquetas le dicen al navegador qué tipo de contenido hay en cada parte de la página. No es obligatorio reemplazar todos los ```<div>```, pero sí es recomendable usar etiquetas semánticas cuando el contenido tenga un significado claro. Los ```<div>``` siguen siendo útiles para agrupaciones generales sin un significado específico.


| Etiqueta | Donde utilizar |
|:-------------:|:---------:|
| ```<header>```| encabezado de la página o sección|
| ```<nav>```   | navegación o menú|
| ```<main>```  | contenido principal|
| ```<section>``` | una sección del contenido|
| ```<article>``` | contenido independiente (como una noticia o post)|
| ```<aside>```   | contenido relacionado o complementario (como una barra lateral)|
| ```<footer>```  | pie de página|


1. Sin HTML semántico (solo con ```<div>```):

No se debe de realizar de este modo ya que hace que el código sea difícil de leer, entender y es más fácil cometer errores o confundirse al dar estilos con CSS, ya que todo parece igual.

```
<div id="header">web</div>
<div id="nav">Inicio | Servicios | Contacto</div>
<div id="main">
  <div class="section">
    <h2>Bienvenido</h2>
    <p>contenido principal</p>
  </div>
</div>
<div id="footer">pie de pagina</div>
```

2. Con HTML semántico:

Usar HTML semántico es correcto porque ayuda a que el código tenga estructura y significado. Cada etiqueta describe el tipo de contenido que contiene.

```
<header>web</header>
<nav>
  <ul>
    <li><a href="#">Inicio</a></li>
    <li><a href="#">Servicios</a></li>
    <li><a href="#">Contacto</a></li>
  </ul>
</nav>
<main>
  <section>
    <h2>Bienvenido</h2>
    <p>contenido principal</p>
  </section>
</main>
<footer>pie de pagina</footer>
```



## Posicionamientos en HTML 

El posicionamiento en HTML no se refiere solo a dónde están los elementos visualmente, sino cómo se comportan dentro del flujo del documento. En CSS, tenemos diferentes maneras de posicionar y distribuir elementos:

* Estático (static): Sigue el flujo normal del HTML.

* Relativo (relative): Se posiciona en base a su lugar original, pero puede moverse.

* Absoluto (absolute): Se posiciona en relación a su elemento padre con position: relative o al body si no hay padre relativo.

* Fijo (fixed):Se queda fijo en la pantalla, aunque hagas scroll.

* Sticky (sticky): Se comporta como relativa hasta que se alcanza una posición y luego se queda fija.


### Resultado al utilizar estos elementos

![posicionamiento](https://github.com/Nahuel-00/Dossier_GitHub_MarkDown_HTML/blob/main/img_html/posicionamiento.png "visualizar como posicionar los elementos en pantalla")


## Rutas en HTML

### ¿Qué son las rutas en HTML?

Las rutas en HTML indican la ubicación de un archivo que quieres usar dentro de tu página web, como imágenes, hojas de estilo (CSS), scripts (JavaScript), otros documentos HTML, etc.
Estas rutas pueden ser relativas o absolutas.

#### Rutas relativas

Las rutas relativas se usan en relación con la ubicación del archivo HTML actual. Es decir, desde el archivo que estás escribiendo, le indicas cómo llegar él.


* ./ → La misma carpeta donde está tu archivo HTML.

```
<img src="./logo.png">
```


* ../ → Sube una carpeta (va al directorio padre).

```
<link rel="stylesheet" href="../css/estilos.css">
```

* carpeta/archivo.ext → Entra en una subcarpeta.
```
<script src="js/app.js"></script>
```

* ../../ → Sube dos niveles (muy útil cuando estás dentro de varias subcarpetas).

```
<img src="../../imagenes/foto.jpg">
```

#### Rutas absolutas

Las rutas absolutas indican la ubicación exacta desde la raíz de los directorios en local o desde una URL.

Desde la raíz en local:
```
<img src="/imagenes/fondo.jpg">
```

Usando una URL:

```
<script src="https://cdn.ejemplo.com/libs/lib.js"></script>
```

- [Volver al inicio](#índice)


# CSS

![css](https://github.com/Nahuel-00/Dossier_GitHub_MarkDown_HTML/blob/main/img_webStyles/css2.png " imagen de styles")


CSS permite dar estilo a páginas web: colores, tamaños, márgenes, tipografías, etc. Se separa el contenido HTML del diseño CSS.



```
<p style="color: blue;">Texto azul con CSS en línea.</p>
```

## ¿Para qué sirve ```<div>```?

Agrupa contenido y permite aplicar estilos. No tiene estilo por defecto.

```
<div style="background: lightgray;">Esto está dentro de un div</div>
```


## Ventajas de usar CSS

Una gran ventaja de usar CSS es que, si lo usamos bien, podemos cambiar el diseño de toda la página desde un solo archivo. Eso nos ahorra tiempo y hace que todo el sitio tenga un mismo estilo. Además, si queremos cambiar algo, como el color de fondo o el tipo de letra, lo hacemos una vez y se actualiza en todas partes.


## Formas de aplicar CSS

Hay tres formas de usar CSS: directamente en las etiquetas HTML (esto no se recomienda mucho), en la parte superior del archivo HTML, o desde un archivo aparte que termina en .css. Esta última es la más adecuada, porque así el diseño está bien separado del contenido.


Se enlaza a una pagina externa de este modo:
```
<link rel="stylesheet" href="estilos.css">
```


## Sintaxis básica de CSS
Cuando usamos CSS, lo que hacemos es seleccionar un elemento y luego decirle cómo queremos que se vea. Por ejemplo, podríamos seleccionar todos los párrafos y decir que el texto sea azul y más grande.

```
p {
  color: red;
  font-size: 16px;
}
```


## Tipos de selectores

* __Etiqueta:__ ```p { color: red; }```

* __Clase:__ ```.caja { background: yellow; }```

* __ID:__ ```#titulo { text-align: center; }```


```
<p class="caja">Texto con clase</p>
```


## Pseudoclases y pseudoelementos

Las pseudoclases sirven para cambiar el estilo dependiendo del estado del elemento, como cuando colocas el mouse por encima de un botón. Y los pseudoelementos permiten modificar solo una parte, como la primera letra de un texto, por ejemplo.

* __Pseudoclase:__ ```a:hover { color: orange; }```

* __Pseudoelemento:__ ```p::first-line { font-weight: bold; }```


## composición. Margenes, bordes y relleno en CSS

Todo lo que colocas en la página se comporta como si estuviera dentro de una caja. Ya sea un párrafo, una imagen o un botón, cada elemento ocupa su espacio como si estuviera dentro de una especie de rectángulo invisible. 

Cada elemento tiene:

* Margin (fuera)

* Border (borde)

* Padding (dentro)

```
.caja {
  margin: 10px;
  border: 1px solid black;
  padding: 5px;
}
```

![cajas](https://github.com/Nahuel-00/Dossier_GitHub_MarkDown_HTML/blob/main/img_webStyles/cajas.png "organizar el contenido")



## Media Queries en CSS

Las media queries son reglas que te permiten aplicar estilos CSS según el tamaño de la pantalla u otras características del dispositivo. Es decir, puedes cambiar el diseño de tu web dependiendo de si se ve en un móvil o en una pantalla grande.

En ordenadores el fondo se ve azul y el texto grande, pero si ves la web en un móvil (pantalla de 600px o menos), el fondo cambia a verde y el texto se hace más pequeño.

```
body {
  background-color: blue;
  font-size: 20px;
}


@media (max-width: 700px) {
  body {
    background-color: green;
    font-size: 16px;
  }
}
```
- [Volver al inicio](#índice)

# Fontawesome


Es una biblioteca de íconos basada en fuentes que permite añadir fácilmente íconos escalables a sitios web mediante HTML y CSS.



![logo de fontawere](https://github.com/Nahuel-00/Dossier_GitHub_MarkDown_HTML/blob/main/img_webStyles/fontw.png "esta el logo de la pagina web de fontawere")



Se utiliza para mejorar la apariencia visual de una página web, incluyendo íconos en menús, botones, formularios y más, sin necesidad de usar imágenes.

Para mostrar un favicon (el ícono que aparece en la pestaña del navegador), debes colocar una línea de código en la sección ```<head>``` de tu documento HTML. Guarda ese archivo que descargues en la misma carpeta donde tienes tu archivo .html o en una carpeta tipo img/ y enlázalo así:



![imagen de descarga](https://github.com/Nahuel-00/Dossier_GitHub_MarkDown_HTML/blob/main/img_webStyles/descargar_archivo.png "esta es la imagen representativa de descarga")



```
<head>
  <link rel="icon" href="./css/file-code-regular.svg">
</head>
```

Al colocar esto se tendrían que visualizar esto en el favicon de la web, el icono cambiará segun el que desees colocar.




![imagen de favicon](https://github.com/Nahuel-00/Dossier_GitHub_MarkDown_HTML/blob/main/img_webStyles/favicon.png "este es el favicon")


- [Volver al inicio](#índice)


# Bootstrap

Se utiliza para diseñar páginas web de forma rápida, sencilla. Este framework incluye estilos prediseñados que se pueden aplicar a botones, formularios, alertas y muchos más elementos. Además de los estilos CSS, Bootstrap también incorpora componentes dinámicos que funcionan con JavaScript, como menús desplegables, carruseles de imágenes, ventanas modales, pestañas, entre otros. Estas funciones permiten añadir interactividad a tu sitio sin tener que programar todo desde cero.

![logo de Bootstrap](https://github.com/Nahuel-00/Dossier_GitHub_MarkDown_HTML/blob/main/img_webStyles/bootstrap-logo.jpg "representación del logo")

Algunas de las ventajas que puede tener es que ahorra tiempo al desarrollar una página web, que ofrece compatibilidad con todos los navegadores, que el diseño es adaptable a cualquier dispositivo.


## Pasos para poder insertar Bootstrap en HTML

* Manera de conseguir los enlaces de Bootstrap

Tendrás que buscar la web oficial de bootstrap y al acceder al ella deberás de hacer scroll hacia abajo y ahí encontrarás los enlaces para añadirlos a tus páginas web.

![insertar Bootstrap](https://github.com/Nahuel-00/Dossier_GitHub_MarkDown_HTML/blob/main/img_webStyles/boot_cdn.png "aqui se podran conseguir los links")


* Incluir el CSS de Bootstrap

Para enlazarlo, utilizamos la etiqueta ```<link>``` dentro de la sección ```<head>``` de tu archivo HTML. Esto asegura que los estilos se carguen primero, antes de mostrar el contenido de la página, y se apliquen correctamente.

```
<head>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.5/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-SgOJa3DmI69IUzQ2PVdRZhwQ+dy64/BUtbMJw1MZ8t5HZApcHrRKUc4W0kG879m7" crossorigin="anonymous">
</head>
```


* Incluir el JS de Bootstrap

También incluye funciones interactivas que requieren JavaScript para funcionar correctamente. Para cargar el archivo JS de Bootstrap de manera eficiente, debes incluirlo justo antes del cierre de la etiqueta ```</body>```. De esta manera, el navegador cargará primero todo el contenido HTML y los estilos CSS, y solo después cargará el JS.

```
<body>

 <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.5/dist/js/bootstrap.bundle.min.js" integrity="sha384-k6d4wzSIapyDyv1kpU366/PK5hCdSbCRGRCMv+eplOQJWyd1fbcAu9OCUj5zNLiq" crossorigin="anonymous"></script>
</body>
```

- [Volver al inicio](#índice)

