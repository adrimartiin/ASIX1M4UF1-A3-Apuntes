# ASIX1M4UF1-A3-Apuntes

Apuntes M4
## Primer capitulo: GITHUB
**Como crear un repositorio**
1. En el dashboard de Github darle a New
2. Nos saldrá un menú donde tendremos que poner un nombre de repositorio, dejar el check de público para que sea público y **IMPORTANTE** darle a añadir el archivo README.
3. Finalmente le daremos a crear repositorio

**Proceso para clonar el repositorio**
Con Github también podremos clonar los repositorios que hayamos creado para poder tenerlos en local y trabajar en ellos. Lo que tendremos que hacer es lo siguiente:
1. En el repositorio que hayamos creado darle al botón de code y copiar el enlace que nos sale debajo
2. Abriremos el CMD 
3. En el CMD pondremos el siguiente comando: git clone (y después de poner git clone) url del repositorio
4. Ya tendremos nuestro repositorio clonado
**IMPORTANTE**: Cuando abramos el CMD nos tendremos que colocar sobre nuestra C y sobre la carpeta de nuestros repositorios que hayamos creado para clonarlo. **Ejemplo**: C:\Repositorio GIT.

**Proceso para subir/actualizar nuestros trabajos que hagamos en local a Github**
1. Guardaremos el trabajo que estemos haciendo con Ctrl+S
2. Abriremos nuestro CMD
3. Cuando lo hayamos abierto, primero de todo, pondremos git init para inicializar Github.
4. A continuación, pondremos git add . para añadir todos los archivos. 
5. Después, pondremos git commit -m "texto que se quiera poner" para guardar lo que hayamos hecho.
6. Finalmente,  pondremos git push origin main para subirlo a github. 

## Segundo capitulo: MARKDOWN

#### SUBTITULO

Este texto esta en *cursiva*
Este texto esta en **negrita**
Este texto esta en **_negrita y cursiva_**
1. Primera opcion de menu
2. Segunda opcion de menu
3. Tercera opcion de menu 

* Primera opcion de lista desordenada
* Segunda opcion de lista desordenada
- Tercera opcion de lista desordenada
    1. Primer submenu
    2. Segundo submenu
- Cuarta opcion de lista desordenada
    * Tercer submenu
    * Cuarto submenu
+ Quinta opcion de lista desordenada
+ Sexta opcion de lista desordenada

#### EJEMPLO DE HTML
```
<html>
    <head>
    </head>
    <body>
        <p>Esto es un parrafo</p>
    </body>
</html>

#### EJEMPLO DE IMAGEN 
```
[Esto es un enlace](http://joan23.fje.edu "Enlace a la web del cole")

![Esto es una imagen]( https://github.com/adrimartiin/ASIX1M4UF1-A3-Apuntes/blob/main/fondopantalla.jpg "Titulo opcional de la imagen")

|Primera Col.|Segunda Col.|3 Col.|
|---------------|:------------:|---------:|
|Col 2 es|Centrada|35€|
|Col 3 es|Derecha|134€|
|Estilo cebra|Gris|Blanco|
|Clase|ASIX1|M4|

- [ ]Opcion A

- [x]Opcion B

- [ ]Opcion C

## Tercer capitulo: HTML

**Como empezar un documento de HTML**

Para empezar un documento HTML, siempre pondremos como tipo de lenguaje del documento HTML. Después de esto en la primera línea pondremos html:5 que genera automáticamente las etiquetas: html,head,body.
**Etiqueta head**: La etiqueta head es la primera etiqueta de la estrcutura de un documento HTML. Podemos ver el título de la página **title**, las etiquetas **meta** y también podremos añadir las etiquetas **link**,**style**,etc.
**Etiqueta body**: En la etiqueta body es donde podremos encontrar todo el cuerpo de nuestro html. Se usan etiquetas como **p** (párrafos), **h1,h2,h3** (encabezados de diferentes tamaños), **ul** (lista desordenada o unordered list), **ol** (lista ordenada o ordered list), **li**(escribir atributos de la lista), **br**(intro) **hr** (línea), **blockquote**(poner una cita),etc.

**Como hacer tablas en html**
Para hacer tablas tendremos que hacer lo siguiente: 
1. Poner la etiqueta **table**
2. Introducirle el borde que queramos de la manera **border=1**
3. Poner la etiqueta **thead** para hacer un encabezado de la tabla
4. Poner la etiqueta **tr** para poner el contenido
5. Poner la etiqueta **tbody** para hacer el cuerpo de la tabla
6. Poner la etiqueta **tr** para poner el contenido del cuerpo de la tabla
7. Poner la etiqueta **tfoot** para poner el pie/final de la tabla
8. Poner la etiqueta **tr** para poner el contenido del pie de la tabla

**Elemento div**

El elemento div es un contenedor para agrupar contenidos y para crear secciones sin significado.

* El borde es el elemento que marca el límite de un elemento que estemos valorando

Los bordes tendrán las siguientes propiedades: 
    
* El valor que indica el grosor nunca puede ser negativo
* Los bordes entre dos bloques estáticos no se colapsan
* 

* El margen es el espacio que separa el div del p. Y tenemos diferentes tipos de margen
    
     * **margin-top:** Es el margen superior
     * **margin-right:** Es el margen derecho
     * **margin-bottom:** Es el margen inferior
     * **margin-left:** Es el margen izquierdo

Y el valor puede ser en píxeles, porcentaje, automático, etc.

* El relleno lo que rellena entre el parrafo y lo del cuerpo

La derivación es igual que la de los margenes solo que cambiando margin por **padding**


## Cuarto capitulo: CSS

**Ventajas y Desventajas de CSS**

Las ventajas que tiene utilizar CSS son:

* Posibilidad de mantener el código
* A nivel de diseño, es mas potente que CSS
* Es un lenguaje sencillo

Y la única desventaja es:

* No todos los navegadores se comportan de la misma forma ante una hoja de estilo dado que algunos no cumplen con los estándares establecidos.

**Ubicaciones**

Podemos ubicar el CSS en diferentes sitios:

1. En la etiqueta, añadiendo el CSS con el elemento **style**.
2. En la **cabecera del documento**: Se pueden poner diferentes propiedades de CSS dentro del elemento style dentro del elemento head
3. En un **documento externo**: Se hace un documento con extension .css y desde el documento HTML se crea un enlace al documento con extensión css  

**Tipos de selectores**

**Selector de elementos:** Corresponde con todos los elementos de el nombre en la página
**Selector de clases:** Corresponde con todos los elementos que tengan el atributo **class** con el valor especificado
**Selector de id*:** Corresponde con todos los elementos que tengan el atributo **id** con el valor especificado
**Selectores universales:** Sirve para seleccionar todos los elementos en la página. Se utiliza con el parámetro *
**Selectores atributos:** Sirve para seleccionar elementos en función de los atributos que contienen
**Selectores de hijos:** Sirve para seleccionar elementos concretos que son hijos directos de otros elementos concretos
**Selectores de descendientes:** Es muy parecido al selector de hijos pero solo seleccionan elementos descendientes DIRECTOS


## Quinto Capítulo: Diseño Responsive
 
 **Que es el diseño responsive**
 El diseño responsive es un tipo de diseño web que permito que un site se ajuste al tamaño de la pantalla. Es decir que se mostrara la pagina web de una manera clara y que sea fácil de navegar.

 **Etiquetas y CSS apropiado para este diseño**
 Las etiquetas que más se utilizan son **div** (al mismo tiempo puede ser **section** o **article**). 
 
 El CSS más apropiado seria poner a cualquier elemento de estos ponerle una clase y en el CSS poner **display:flex;**. Esto hace que cada div se coloque como si fuesen celdas en una tabla y que se ajuste al lugar de la web donde esté. 

 Otra etiqueta importante es el **float** que lo que hace es colocar en el lado izquierdo o derecho para que los elementos se ajusten correctamente. Un ejemplo de como se debe utilizar es **float: left**


 **Otros contenidos**

 También tenemos **media-only** que pone un grupo de declaraciones en un CSS con una condición definida. Para ponerlo, debe ser de la siguiente manera: **@media only (parametros)**
