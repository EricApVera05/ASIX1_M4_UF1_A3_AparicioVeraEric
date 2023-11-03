# ASIX1_M4_UF1_A3_AparicioVeraEric

06/10/2023
HTML
======================
Las etiquetas se dividen en etiquetas de apertura y etiquetas de cierre.
```
<p>contenido visible</p>
------------------------
        elemento
```


```
<p class="valor"> contenido </p>
```

Se pueden anidar etiquetas.
```
<p>XXXXXX<strong>negrita</strong>XXXXXXX</p>
```

Las imagenes no necesitan etiqueta de cierre.
```
<img href="./XXXX">
```


Al crear un archivo plano debemos especificar el lenguaje que se va a utilizar.

si establecemos el comando html:5 nos crea la estructura basica de un documento html.

DOCTYPE indica el tipo de documento que es nuestro archivo.

En la etiqueta HTML hay un atributo lang que muestra el idioma en el que está la pagina.

El bloque HEAD va al principio de la pagina, es la parte donde definimos las caracteristicas de la pagina y añadimos el contenido no visible para los visitantes de la pagina. Se pueden establecer favicon para añadir un icono a la pagina web.

El bloque BODY se añade toda la parte visible para el usuario. 
Se divide en categoria de etiquetas de bloque y etiquetas de linea.
EB->Cuando termina de renderizar el contenido crea un espaciado aunque esten juntas en la linea HTML.
EJ:Titulos, parrafos, listas y tablas.

EL-> No crea espaciado a menos que termine el bloque.

EJ: Enlaces, estilos (negrita, subrallado...), y imagenes.

H1 crea titulos

H3 crea subtitulos
```
<ol>crea una lista ordenada
    <li>crea elementos</li>
    <li>segundo elemento</li>
    <li>tercer elemento</li>
</ol>
```

<ol>crea una lista ordenada
    <li>crea elementos</li>
    <li>segundo elemento</li>
    <li>tercer elemento</li>
</ol>

```
<ol>
    <ul> crea una lista desordenada
       <li>elementos de nivel 2</li>
       <li> elemento de nivel 2</li>
       <li>elemento de nivel 2</li>
   </ul>
</ol>
```

<ol> crea una lista ordenada
    <li>elemento nivel 1</li>
    <ul> crea una lista desordenada
       <li>elementos de nivel 2</li>
       <li> elemento de nivel 2</li>
       <li>elemento de nivel 2</li>
   </ul>
   <li>elemento nivel 1</li>
</ol>
</br>
<a href="https://www.google.es" target="_blank">Google</a>



añadimos en el head este codigo: 
```
<script src="https://kit.fontawesome.com/05bd12561e.js" crossorigin="anonymous"></script> 
```

añadimos este codigo:
```
<i class="fa-brands fa-github">Github</i>
```
