# notas clase 2

## Atributos
> Los atributos son modificadores de un elemento

<elemento atributo="valor"> contenido </elemento>
<elemento atributo="valor" atributo2="valor2"> contenido </elemento>


## Enlaces o vínculos

<a href="url" target="_blank">contenido</a>

## Imágenes

<img src="ruta">
<img src="ruta" alt="descripción">

> El atributo alt se utiliza para escribir una descripción de la imagen que se utilizará para visitantes de nuestro sitio que tengan alguna discapacidad visual
> Queríamos utilizar alguna descripción breve ya que el usuario que ingrese con las opciones de accesibilidad en su navegador va a oír esta descripción


### Sitios para descargar imágenes

    íconos  
        Flaticon <https://www.flaticon.com/>
        Freepik <https://www.freepik.com/icons>
        SVGRepo <https://www.svgrepo.com/>

    fotografías
        Unsplash <https://unsplash.com/es>
        Pexels  <https://www.pexels.com/es-es/>
        Freepik <https://www.freepik.com/>

### Sitio de generación de imágenes por IA

    Grok  <https://grok.com/>      
    ChatGPT <https://chatgpt.com/>
    Gemini  <https://gemini.google.com/app>
    Leonardo <https://app.leonardo.ai/>  
    Higgsfield <https://higgsfield.ai/>

### Sitio para cambiar el tamaño de una imagen
> En este sitio también podemos cambiar el encuadre y hasta rotar una imagen

<https://imageresizer.com/>

### Aplicación para diseño de imágenes y foto edición
  Affinity <https://www.affinity.studio/es_es/get-affinity>


## Estructura de un documento html
> Cuando generamos un documento html este debe tener la siguiente estructura:

<!DOCTYPE html>
<html>
    <head>
        Elementos NO visuales (no se ven directamente dentro de la página)
    </head>
    <body>
        Elementos visuales (se ven directamente dentro de la página)
    </body>
</html>

> Todo el contenido que queremos ver dentro de la página debería estar dentro del elemento body

    párrafos    
    imágenes    
    video

## Enunciados o encabezados
    <h1>¿Qué son los encabezados en HTML?</h1>
    
    <p>
        Los encabezados (o headings) son elementos que van desde el h1 hasta el h6 y se utilizan para definir la jerarquía del contenido en una página web. 
    </p>
    <p>Imagina que tu sitio es un libro: el h1 sería el tema principal de la obra, los h2 serían los capítulos, y los h3 representarían los subapartados dentro de esos capítulos. 
    <br>
    Esta estructura ayuda a que los usuarios puedan escanear el contenido rápidamente y entender de qué trata cada sección.
    </p>

    <h2>La importancia de la jerarquía</h2>
    
    <p>Es fundamental seguir un orden lógico y no saltarse niveles. Por ejemplo, nunca deberías pasar de un h1 directamente a un h3 sólo porque prefieres un tamaño de letra más pequeño; para eso existe el diseño con CSS.<br>
    El uso correcto de los niveles (del 1 al 6) permite que las herramientas de asistencia, como los lectores de pantalla para personas con discapacidad visual, naveguen por el documento de manera coherente.
    </p>

    <h2>SEO y Semántica</h2>

    <p>Desde el punto de vista del SEO (Optimización para Motores de Búsqueda), el encabezado h1 es el más importante, ya que indica el tema central de la página. Google y otros buscadores analizan estos elementos para indexar tu contenido correctamente. <br>
    Por lo general, se recomienda tener un solo h1 por página para evitar confusiones sobre cuál es el tema principal, mientras que el resto de los niveles pueden usarse tantas veces como sea necesario para organizar la información.</p>

## CSS (Cascading Style Sheets)


> Es el lenguaje encargado de aportar toda la parte estética de nuestras páginas
> Estamos hablando de color, tamaño, tipografía y posición de los elementos

> En CSS tenemos reglas: estas son los conjuntos de atributos que vamos a utilizar para aplicar la parte estética
> Sintaxis: 

    selector{  
        atributo:valor;  
        atributo2:valor2;  
        atributo3:valor3;  
    }