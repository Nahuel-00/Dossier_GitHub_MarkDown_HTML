# GitHub

[//]: <> (indice, si clicas en una opcion te dirige automaticamente)

- [GitHub](#GitHub)
- [MarkDown](#MarkDown)
- [HTML](#HTML)

## Acerca de GitHub

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



- [Volver al índice](#GitHub)

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

- [Volver al índice](#GitHub)

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

![imagen validador](https://github.com/Nahuel-00/Dossier_GitHub_MarkDown_HTML/blob/main/img_html/campo_de_texto.png "esta es la pagina web del validador")


### Campo de contraseña

A diferencia del campo de texto normal, los caracteres escritos no se muestran en pantalla, sino que aparecen como puntos o asteriscos

```
<input type="password" name="clave" id="clave" />
```
![imagen validador](https://github.com/Nahuel-00/Dossier_GitHub_MarkDown_HTML/blob/main/img_html/campo_de_contase%C3%B1a.png "esta es la pagina web del validador")

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

![imagen validador](https://github.com/Nahuel-00/Dossier_GitHub_MarkDown_HTML/blob/main/img_html/radi.png "esta es la pagina web del validador")

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

![imagen validador](https://github.com/Nahuel-00/Dossier_GitHub_MarkDown_HTML/blob/main/img_html/checkbox.png "esta es la pagina web del validador")

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

![imagen validador](https://github.com/Nahuel-00/Dossier_GitHub_MarkDown_HTML/blob/main/img_html/menu.png "esta es la pagina web del validador")

### Área de texto (textarea)

Sirve para escribir comentarios o textos largos.

```
<label for="observaciones">observaciones</label><br>
<textarea name="observaciones" id="observaciones" cols="80" rows="4" placeholder="introduce tus comentarios"></textarea>
```

![imagen validador](https://github.com/Nahuel-00/Dossier_GitHub_MarkDown_HTML/blob/main/img_html/textarea.png "esta es la pagina web del validador")

### Botón


Sirve para enviar el formulario.

```
<button type="submit">Enviar datos</button>
```

![imagen validador](https://github.com/Nahuel-00/Dossier_GitHub_MarkDown_HTML/blob/main/img_html/boton.png "esta es la pagina web del validador")

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



## Posicionamientos en HTML 




## Rutas en HTML






## Fontawesome


Es una biblioteca de íconos basada en fuentes que permite añadir fácilmente íconos escalables a sitios web mediante HTML y CSS.



![imagen validador](https://github.com/Nahuel-00/Dossier_GitHub_MarkDown_HTML/blob/main/img_webStyles/fontw.png "esta es la pagina web del validador")



Se utiliza para mejorar la apariencia visual de una página web, incluyendo íconos en menús, botones, formularios y más, sin necesidad de usar imágenes.

Para mostrar un favicon (el ícono que aparece en la pestaña del navegador), debes colocar una línea de código en la sección ```<head>``` de tu documento HTML. Guarda ese archivo que descargues en la misma carpeta donde tienes tu archivo .html o en una carpeta tipo img/ y enlázalo así:



![imagen validador](https://github.com/Nahuel-00/Dossier_GitHub_MarkDown_HTML/blob/main/img_webStyles/descargar_archivo.png "esta es la pagina web del validador")



```
<head>
  <link rel="icon" href="./css/file-code-regular.svg">
</head>
```

Al colocar esto se tendrían que visualizar esto en el favicon de la web, el icono cambiará segun el que desees colocar.




![imagen validador](https://github.com/Nahuel-00/Dossier_GitHub_MarkDown_HTML/blob/main/img_webStyles/favicon.png "esta es la pagina web del validador")




## Bootstrap

Se utiliza para diseñar páginas web de forma rápida, sencilla. Este framework incluye estilos prediseñados que se pueden aplicar a botones, formularios, alertas y muchos más elementos. Además de los estilos CSS, Bootstrap también incorpora componentes dinámicos que funcionan con JavaScript, como menús desplegables, carruseles de imágenes, ventanas modales, pestañas, entre otros. Estas funciones permiten añadir interactividad a tu sitio sin tener que programar todo desde cero.

![imagen validador](https://github.com/Nahuel-00/Dossier_GitHub_MarkDown_HTML/blob/main/img_webStyles/bootstrap-logo.jpg "esta es la pagina web del validador")

Algunas de las ventajas que puede tener es que ahorra tiempo al desarrollar una página web, que ofrece compatibilidad con todos los navegadores, que el diseño es adaptable a cualquier dispositivo.


### Pasos para poder insertar Bootstrap en HTML

1. Manera de conseguir los enlaces de Bootstrap

Tendrás que buscar la web oficial de bootstrap y al acceder al ella deberás de hacer scroll hacia abajo y ahí encontrarás los enlaces para añadirlos a tus páginas web.

![imagen validador](https://github.com/Nahuel-00/Dossier_GitHub_MarkDown_HTML/blob/main/img_webStyles/boot_cdn.jpg "esta es la pagina web del validador")


1. Incluir el CSS de Bootstrap

Para enlazarlo, utilizamos la etiqueta ```<link>``` dentro de la sección ```<head>``` de tu archivo HTML. Esto asegura que los estilos se carguen primero, antes de mostrar el contenido de la página, y se apliquen correctamente.

```
<head>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.5/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-SgOJa3DmI69IUzQ2PVdRZhwQ+dy64/BUtbMJw1MZ8t5HZApcHrRKUc4W0kG879m7" crossorigin="anonymous">
</head>
```


2. Incluir el JS de Bootstrap

También incluye funciones interactivas que requieren JavaScript para funcionar correctamente. Para cargar el archivo JS de Bootstrap de manera eficiente, debes incluirlo justo antes del cierre de la etiqueta ```</body>```. De esta manera, el navegador cargará primero todo el contenido HTML y los estilos CSS, y solo después cargará el JS.

```
<body>

 <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.5/dist/js/bootstrap.bundle.min.js" integrity="sha384-k6d4wzSIapyDyv1kpU366/PK5hCdSbCRGRCMv+eplOQJWyd1fbcAu9OCUj5zNLiq" crossorigin="anonymous"></script>
</body>
```

- [Volver al inicio](#GitHub)

