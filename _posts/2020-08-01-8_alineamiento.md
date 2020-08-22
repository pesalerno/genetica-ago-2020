---
layout: default
order: 8
title:  "Taller alineamiento y modelos de mutacion"
date: 2020-08-01
time:   "viernes 21 Ago"
categories: main
instructor: "Pati"
materials: ""
material-type: ""
lesson-type: autoguiada, evaluada
---

<a href="https://pesalerno.github.io/genetica-ago-2020/main/2020/06/08/7_geno-feno-2.html"><button>Actividad Anterior</button></a>		<a href="https://pesalerno.github.io/genetica-ago-2020/"><button>Inicio</button></a>    <a href="https://pesalerno.github.io/genetica-ago-2020/main/2020/06/09/9_proyectos-2.html"><button>Siguiente Actividad</button></a>

# Taller de alineamiento 


>**PÁGINA EN CONSTRUCCIÓN. FAVOR REVISAR MÁS TARDE**



> -------------------
> 
> **VIERNES 9-10:30am** | Sesión Sincrónica para discutir el contenido de las dos actividades anteriores (*'Genotipo a Fenotipo'*) y para discutir cómo funcionará el taller de alineamiento. 
> 
> ------------------------ 
 
 
Los alineamientos de genes sirven para muchas cosas: nos ayudan a reconstruir historias evolutivas de grupos taxonómicos, nos permiten identificar "variantes" clínicos para identificar alelos responsables de ciertas patologías/cánceres, nos permiten describir poblaciones de animales en peligro de extinción y su capacidad adaptativa, entre muchas otras apliaciones. 

![](https://github.com/pesalerno/genetica-ago-2020/blob/master/files/rDNA.png?raw=true)<br>

En este taller, aprenderemos lo básico acerca de los marcadores genéticos y su historia, y de cómo los marcadores ribosomales - como el 16s - son usados para estudiar la mayor cantidad de vida en el planeta. Entenderemos lo díficil que es el concepto de "homología" con genética, despues de todo teniendo sólo cuatro bases, la probabilidad es altísima de que dos `A` sean iguales debido a homología o a convergencia, lo cual se hace particularmente difícil dada la estructura del `rDNA`. 


>--------------------------
>
>**VIDEO:** En [este video]() de ~45min les doy una introducción a los marcadores genéticos y a la secuenciación Sanger.  
>
>--------------------------


## Comenzando con bajar nuestras secuencias


Primero, escojan su grupo de estudio, el cual debe ser relativamente "pequeño", respecto al árbol de la vida: un género, una especie, como mucho una familia. De ese grupo taxonómico que escogieron, deben bajar un total de 10 secuencias del marcador `16S rRNA`, un fragmento ribosomal codificado por la mitocondria, y el cual es comúnmente secuenciado para una gran variedad de eucariotas. 


Segundo, vayan a la [página de NCBI](https://www.ncbi.nlm.nih.gov/nuccore/) donde pueden acceder a las secuencias genéticas disponibles públicamente. Allí, deben hacer una búsqueda, en el caso mío, yo busqué `16S Pseudacris`, el cual es un género de ranas arboríolas de Norteamérica. 

![](https://github.com/pesalerno/genetica-ago-2020/blob/master/files/ncbi.png?raw=true)<br>

Cuando salen los resultados, ven que hay un montón!! ademas de eso, noten los nombres de los archivos... algunos contienen sólo la secuencia del gen, pero otros contienen un mónton de otros genes (12s por ejemplo).



Entonces, intenten escoger casi todos que únicamente contengan 16s, pero si tienen alguno que tenga más genes (tanto `downstream` como `upstream`), entonces lo pueden agregar. Básicamente, lo que ocurre es que a veces la gente amplifica y secuencia segmentos mitocondriales bastante grandes, por lo que verán que los nombres de las secuencias pueden contener genes adyacentes. 

Para referencia, así se ve el genoma mitocondrial de los eucariotas (es decir, de ustedes): 

![](https://github.com/pesalerno/genetica-ago-2020/blob/master/files/mtDNA-genome.png?raw=true)<br>

Regresando a la búsqueda que yo hice, de `Pseudacris`, una vez que sa sé cuales secuencias quiero bajar, las "escojo" haciendo "click" en la selección a TODAS las secuencias a la vez, y escojo `Send To>Complete Record>File>Fasta>Create File` tal como se observa en la foto de abajo:

![](https://github.com/pesalerno/genetica-ago-2020/blob/master/files/pseudacris-download.png?raw=true)<br>


Luego, ese archivo que bajen lo agregan (hacen "upload") directamente a la página del programa de alineamiento [`Clustal Omega`](https://www.ebi.ac.uk/Tools/msa/clustalo/), el cual va a generar un alineamiento de nuestras secuencias. Sólo hay que especificar que el "input" son decuencias de `DNA` y que el "output" es en el formato `NEXUS`.  

![](https://github.com/pesalerno/genetica-ago-2020/blob/master/files/clustal-input.png?raw=true)<br>

De ahi, puede hacer "download" del archivo, donde podrán ver el alineamiento "cortado" (en ingles "interleaved") de nexus el cual usaremos para visualizar a más detalle. 


![](https://github.com/pesalerno/genetica-ago-2020/blob/master/files/clustal-output.png?raw=true)<br>


Finalmente, en el programa [Mesquite](https://www.mesquiteproject.org/Installation.html), que pueden descargar para cualquier tipo de computador en el enlace anterior, podemos vizualizar nuestro alineamiento de modo mucho mas fácil, así como editarlo (por ejemplo para eliminar las bases en exceso que sólo están presentes en algunos individuos).



![](https://github.com/pesalerno/genetica-ago-2020/blob/master/files/mesquite-align.png?raw=true)<br>



 
 
<a href="https://pesalerno.github.io/genetica-ago-2020/main/2020/06/08/7_geno-feno-2.html"><button>Actividad Anterior</button></a>		<a href="https://pesalerno.github.io/genetica-ago-2020/"><button>Inicio</button></a>    <a href="https://pesalerno.github.io/genetica-ago-2020/main/2020/06/09/9_proyectos-2.html"><button>Siguiente Actividad</button></a>






