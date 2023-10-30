# Estructura de un proyecto web

## Proyecto Simple

### Tree

```
simple-web-project-structure/
│
├─ public/ 
│  ├─ assets/ 
│  │  ├─ icons/ 
│  │  ├─ img/
│  │  ├─ fonts/ 
│  │  └─ media/
│  │     ├─ audio/
│  │     └─ video/
│  ├─ css/ 
│  ├─ js/ 
│  └─ index.html
│
└─ src/
   ├─ assets/
   ├─ css-scss/ 
   ├─ database/
   │  └─ archivo-db.sql
   ├─ docs/
   │  └─ guide.md
   ├─ js/
   │  ├─ helpers/ 
   │  ├─ modules/
   │  └─ index.js
   └─ views/
```

### Carpetas

La carpeta [public]() es la que contiene todo el [entorno de distribución]() y aquí se encuentran todos los archivos ya [procesados]() (es decir, archivos comprimidos, mimificados, sin comentarios ni espacios innecesarios) listos para la entrega final del proyecto y para subirlos al servidor.

- La carpeta [assets]() es la que contiene todos los archivos extra al código como las imagenes, audios, video no disponibles publicamente en internet, solo propios del proyecto
  
  - La carpeta [icons]() contiene los iconos unicos propios del proyecto, las extensiones para estos archivos deben ser en .png o .svg
    
  - La carpeta [img]() tiene todas las imagenes utilizadas para banners, galerías, etc. utilizadas para el proyecto.
    
  - La carpeta [fonts]() tiene las fuentes y tipografía unicas del proyecto, ya sean estas creadas o compradas para utilizarlas en el sitio web.
    
  - La carpeta [media]() sera la carpeta relativa a los archivos multimedia como adios y videos, dentro de esta tendra una carpeta por cada tipo de archivo.
    
    - [audio]()
      
    - [video]()
      
- La carpeta [css]() o [scss]() enteramente contiene solo archivos utilizados para los estilos del frontend, al ya estar procesado se encuentra solo un [styles.css]() de una sola línea.
  
- La carpeta [js]() contiene los archivos de javascript, que al ya estar procesados se encuentra solo uno llamado [scripts-min.js]() con todas las funciones concatenadas.
  
- Finalmente el archivo [index.html]() y el resto de los archivo [html]() de las paginas del sitio.
  

La carpeta [dev]() o [src]() comunmente es utilizada por herramientas para la estructuración de proyectos, aquí es donde se encuentra el [entorno de desarrollo]() y es donde se estara trabajando en cuestion al desarrollo del proyecto.

- La carpeta [assets]() sera igual que la carpeta encontrada en [public](), sin embargo en esta, todos los archivos aún estan sin ser tratados ni procesados.
  
- La carpeta [css]() o [scss]() enteramente contiene todos los archivos relativos a los html utilizados para el proyecto.
  
- La carpeta [database]() tendra el o los archivos [.sql]() enfocados a la base de datos, procedimientos y triggers.
  
- La carpeta [docs]() concentra todos los archivos informativos al contenido del proyecto, su funcionamiento, procedimientos, funciones y el manual de navegacion de usuaios, generalmente estos archivos se encuentran con la extención [.doc](), [.txt]() o [.md]().
  
- La carpeta [js]() contiene los archivos de javascript, que contienen las acciones o funciones que haran ciertos componentes del sitio.
  
  - La carpeta [helpers]() tiene todos los archivos con funciones de ayuda
    
  - La carpeta [modules]() matiene el archivo o archivos con modulos repetitivos y relativos a las paginas.
    
  - El archivo [index.js]() mantiene las acciones y funciones generales del sitio, aqui es donde se importan los demás archivos [.js]().
    
- La carpeta [views]() contendra todos los archivos de las paginas del proyecto ya sean [html]() o en dado caso de estar ocpado herramientas externas [pug]().
  

> **NOTA:** Para optimizar el código [css]() se puede hacer uso de la herramineta [Gulp](https://gulpjs.com/) y para transpilar el código de [js]() sepuede utilizar babel.

### Créditos

Este proyecto fue inspirado en la metodología desarrollada por @DorianDesings

Github: [github.com/DorianDesings](github.com/DorianDesings)

YouTube: [youtube.com/@DorianDesings/featured](https://www.youtube.com/@DorianDesings/featured)

Video de YouTube: [youtube.com/watch?v=yo8Y2hB5A9A](https://www.youtube.com/watch?v=yo8Y2hB5A9A)
