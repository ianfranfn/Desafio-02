# Introducción al FODA - Desafío 01

Se empieza agregando el título de la página (Semana 1) y seguido a eso se abre el título "Análisis FODA". 

```sh
<Title> Semana 1 </title>
<h1> Análisis FODA </h1>
```

## Etiquetas

Las etiquetas utilizadas son:

```sh
<h1> Hasta <h4> para el título y subtítulos
<p> Para los párrafos 
<li> Para enlistar
<ul> Para las listas desordenadas
<br> Para hacer salto de línea
<em> Para usar cursiva en énfasis semántico
<b> Para usar negrita
<strong> Para usar negrita con énfasis semántico
<i> Para usar Cursiva.
```

## Cuerpo del texto

Se añaden los objetivos y partes que componen un análisis FODA, además de sus características internas y externas como sus fortalezas, debilidades, oportunidades y amenazas. 

## Datos alumno

Nombre: Fariña Núñez Ian Franco
Repo GitHub: https://github.com/ianfranfn/Desafio-02.git
Netlify: https://bespoke-belekoy-b66ed1.netlify.app/

# Introducción al FODA - libre - Desafío 02

Se da inicio a la libreria VITE mediante el gestor de dependencias NPM

```sh
En la consola:

npm create vite@latest ./
---> Vanilla
---> Javascript.js
npm install 
npm run dev
```
Luego se añaden los archivos Index.html y README.md del desafío 01.

## Clases, fuentes y colores

Se añaden los colores principales del FODA (verde, azul, amarillo y rojo) y una nueva fuente de prueba para los "h2" vínculada desde la página web "Google Fonts", asi como nuevas clases para resaltar textos de importancia para el lector.

```sh
<h2 class="texto-verde/azul/amarillo/rojo"> texto </h2>
<h2 class="subtitulos">texto</h2>
<p class="texto-resaltado"> parte-de-parrafo </p>

Fuente importada:

@import url('https://fonts.googleapis.com/css2?family=Lugrasimo&display=swap');
```

## Imágenes

Se añaden nuevas imágenes en formato .webp adaptadas a la página, cada una en el lugar correpondiente y con su descripción.

```sh
 <img src="/imgs/ejemplo-analisis-foda.webp" alt="Descripción de la imágen">
```

## Links

Se hace el uso de hipervínculos con otras partes de la página. Cada una tiene su contenido e imágenes correspondientes para facilitar el entendimiento de la lectura, así como el uso de las clases (cuando es necesario o útil).

```sh
 <a href="../index.html">Inicio</a>
 <a href="FODA/planificar.html">planificar</a>
 <a href="FODA/matriz-foda.html">Matriz FODA</a>
```

## Datos actualizados del alumno

Nombre: Fariña Núñez Ian Franco
Repo GitHub: https://github.com/ianfranfn/Desafio-02.git
Netlify: 