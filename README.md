# ASIX1_M4_UF1_A3_AparicioVeraEric
GIT
======================
git init: Inicializa un repositorio.

git add: Añade cambios al área de preparación.

git commit: Guarda los cambios en el repositorio.

git push: Sube cambios a un repositorio remoto.

git pull: Descarga cambios de un repositorio remoto.

git branch: Muestra y crea ramas.

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

<h1> 03/11/2023 CSS</h1>
3 Formas de implementar
En la propia etiqueta (puntual)
Estilo in-line
Primero se define a que elemento afecta (selector)
Lo siguiente son las declaraciones;
selector declaracion:valor;
Tiene prioridad frente a la inserción interna.

En el Head (afectación a varios elementos de una misma pagina)
Inserción Interna

Archivo externo [Utilización en todas(o varias) las paginas del site]
Inserción Externa
Para insertar de manera externa debemos añadir un link para enlazar el otro documento.

Selectores

Universal 
Sintaxis: * {}

Selector etiqueta
Sintaxis: etiqueta { atributo:valor }

Selector clase
Sintaxis: .clase { atributo:valor }

Selector ID
Un selector de ID está diseñado para seleccionar elementos con base en su atributo de ID.
Sintaxis: #id{}

Combinacion de selectores
La combinación de selectores nos permite dar un estilo a todos los selectores indicados.
Sintaxis: selector1, selector2{}

Selector de hijos
Se usa para seleccionar un elemento que es hijo de otro elemento.
Diferencia entre selector de hijos y selector descendiente. Los hijos son los elementos que se encuentran un nivel directamente debajo de el mismo elemento section. Los descendientes son todos los elementos que se encuentran dentro del elemento section sean los mismos hijos o los hijos de los hijos.
Sintaxis: selector1 > selector2 {}

Selector descendiente
Un elemento es descendiente de otro cuando se encuentra entre las etiquetas de apertura y de cierre del elemento padre.
Sintaxis: selector1 selector2{}

13/12/2023

DIV
======================
Estructura los elementos.

El bloque se adapta al contenido que tenga dentro

El borde es la linea perimetral que divide un elemento de otro

El margen es la separacion exterior entre un contenedor y otro.

El Padding es la separacion en el interior del div.

Responsive
======================
El diseño responsive se refiere a la capacidad de una interfaz web o aplicación para adaptarse y proporcionar una experiencia de usuario óptima en una variedad de dispositivos y tamaños de pantalla. Esto se logra mediante el uso de técnicas y tecnologías como media queries, flexbox, y grid layout.
Media Queries: Utiliza consultas de medios para aplicar estilos específicos según el tamaño de la pantalla.
```
@media only screen and (max-width: 600px) {
  /* Estilos para pantallas con ancho máximo de 600px */
  ...
}

```
Utilizamos flex y grid para crear diseños adaptables.
```
.container {
  display: flex;
  justify-content: space-between;
}

.grid-container {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
}

```
Imágenes Responsive: Utilizamos max-width: 100%; en imágenes para que se ajusten al tamaño de su contenedor.

```
img {
  max-width: 100%;
  height: auto;
}

```

