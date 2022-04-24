# [Bayesian Methods for Hackers](http://camdavidsonpilon.github.io/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/)
#### *Using Python and PyMC*


El método bayesiano es el enfoque natural de la inferencia, pero está oculto a los lectores detrás de los capítulos del análisis lento y matemático. El texto típico en la inferencia de Bayesia involucra de dos a tres capítulos sobre la teoría de la probabilidad, luego ingresa la inferencia bayesiana. Desafortunadamente, debido a la intractabilidad matemática de la mayoría de los modelos bayesianos, el lector solo se muestran ejemplos simples y artificiales. Esto puede dejar al usuario con un * así que * Sentirse de la inferencia bayesiana. De hecho, esta fue la propia opinión anterior del autor.

Después de un éxito reciente de los métodos bayesianos en las competiciones de aprendizaje automático, decidí investigar el tema nuevamente. Incluso con mi fondo matemático, me tomó tres días seguidos de lectura de ejemplos y tratando de juntar las piezas para comprender los métodos. Simplemente no había suficiente teoría de la literatura para practicar. El problema con mi malentendido fue la desconexión entre las matemáticas bayesianas y la programación probabilística. Dicho esto, sufrí que el lector no tendría que ahora. Este libro intenta cerrar la brecha.

Si la inferencia bayesiana es el destino, entonces el análisis matemático es un camino particular hacia ella. Por otro lado, la potencia de computación es lo suficientemente barata de que podamos permitirnos tomar una ruta alternativa a través de la programación probabilística. El último camino es mucho más útil, ya que niega la necesidad de la intervención matemática en cada paso, es decir, eliminamos el análisis matemático a menudo intratable como un requisito previo para la inferencia bayesiana. En pocas palabras, este último camino computacional procede a través de pequeños saltos intermedios de principio a fin, donde la primera ruta procede de enormes saltos, a menudo aterrizando lejos de nuestro objetivo. Además, sin un fondo matemático fuerte, el análisis requerido por la primera ruta ni siquiera puede tener lugar.

* Los métodos bayesianos para hackers * están diseñados como una introducción a la inferencia bayesiana de un punto de vista computacional / comprensivo: primero, y matemáticas, segundo, punto de vista. Por supuesto, como un libro introductorio, solo podemos dejarlo al respecto: un libro de introducción. Para los matemáticamente capacitados, pueden curar la curiosidad, este texto genera con otros textos diseñados en mente con el análisis matemático. Para los entusiastas, con menos antecedentes matemáticos, o uno que no está interesado en las matemáticas, sino simplemente la práctica de los métodos bayesianos, este texto debe ser suficiente y entretenido.

La elección de PYMC, ya que el lenguaje de programación probabilístico es dos veces. En este momento, actualmente no hay recurso central para ejemplos y explicaciones en el universo PYMC. La documentación oficial asume el conocimiento previo de la inferencia bayesiana y la programación probabilística. Esperamos que este libro alienta a los usuarios a todos los niveles para mirar a PYMC. En segundo lugar, con los recientes desarrollos básicos y la popularidad de la pila científica en Python, es probable que PyMC se convierta en un componente central lo suficientemente pronto.

PyMC tiene dependencias para ejecutar, a saber, numerable y (opcionalmente) Scipy. Para no limitar al usuario, los ejemplos en este libro se basarán solo en PYMC, NOMBRY, SCIPY y MATPLOTLIB.


Versión impresa por Addison-Wesley
------
<div style="float: right; margin-left: 30px;"><img title="Bayesian Methods for Hackersg"style="float: right;margin-left: 30px;" src="http://www-fp.pearsonhighered.com/assets/hip/images/bigcovers/0133902838.jpg" align=right height = 200 /></div>

**¡Los métodos bayesianos para hackers ahora están disponibles como un libro impreso! ** Puedes recoger una copia en [Amazon](http://www.amazon.com/Bayesian-Methods-Hackers-Probabilistic-Addison-Wesley/dp/0133902838). ¿Cuáles son las diferencias entre la versión en línea y la versión impresa?

 - Capítulo adicional sobre las pruebas de Bayesian A / B
 - Ejemplos actualizados
 - Respuestas al final de las preguntas del capítulo.
 - Explicación adicional, y secciones reescritas para ayudar al lector.


Contenido
------

Ver la página de inicio del proyecto [here](http://camdavidsonpilon.github.io/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/) for examples, too.


The below chapters are rendered via the *nbviewer* at
[nbviewer.jupyter.org/](http://nbviewer.jupyter.org/), and is read-only and rendered in real-time.
Interactive notebooks + examples can be downloaded by cloning! 

### PyMC2

* [**Prologue:**](http://nbviewer.jupyter.org/urls/raw.github.com/CamDavidsonPilon/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/master/Prologue/Prologue.ipynb) Why we do it.

* [**Capítulo 1: Introducción a los métodos bayesianos.**](http://nbviewer.jupyter.org/urls/raw.github.com/CamDavidsonPilon/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/master/Chapter1_Introduction/Ch1_Introduction_PyMC2.ipynb)
    Introduction to the philosophy and practice of Bayesian methods and answering the question, "What is probabilistic programming?" Examples include:
    - Inferring human behaviour changes from text message rates
    
* [**Capítulo 2: un poco más sobre PYMC**](http://nbviewer.jupyter.org/urls/raw.github.com/CamDavidsonPilon/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/master/Chapter2_MorePyMC/Ch2_MorePyMC_PyMC2.ipynb)
    We explore modeling Bayesian problems using Python's PyMC library through examples. How do we create Bayesian models? Examples include:
    - Detecting the frequency of cheating students, while avoiding liars
    - Calculating probabilities of the Challenger space-shuttle disaster
    
* [**Capítulo 3: Apertura de la caja negra de MCMC**](http://nbviewer.jupyter.org/urls/raw.github.com/CamDavidsonPilon/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/master/Chapter3_MCMC/Ch3_IntroMCMC_PyMC2.ipynb)
    We discuss how MCMC operates and diagnostic tools. Examples include:
    - Bayesian clustering with mixture models
    
* [**Capítulo 4: El teorema más grande nunca le dijo**](http://nbviewer.jupyter.org/urls/raw.github.com/CamDavidsonPilon/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/master/Chapter4_TheGreatestTheoremNeverTold/Ch4_LawOfLargeNumbers_PyMC2.ipynb)
    We explore an incredibly useful, and dangerous, theorem: The Law of Large Numbers. Examples include:
    - Exploring a Kaggle dataset and the pitfalls of naive analysis
    - How to sort Reddit comments from best to worst (not as easy as you think)
    
* [**Capítulo 5: ¿Prefieres perder un brazo o una pierna?**](http://nbviewer.jupyter.org/urls/raw.github.com/CamDavidsonPilon/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/master/Chapter5_LossFunctions/Ch5_LossFunctions_PyMC2.ipynb)
    The introduction of loss functions and their (awesome) use in Bayesian methods.  Examples include:
    - Solving the *Price is Right*'s Showdown
    - Optimizing financial predictions
    - Winning solution to the Kaggle Dark World's competition
    
* [**CAPÍTULO 6: Obtención de las prioridades**](http://nbviewer.jupyter.org/urls/raw.github.com/CamDavidsonPilon/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/master/Chapter6_Priorities/Ch6_Priors_PyMC2.ipynb)
    Probably the most important chapter. We draw on expert opinions to answer questions. Examples include:
    - Multi-Armed Bandits and the Bayesian Bandit solution.
    - What is the relationship between data sample size and prior?
    - Estimating financial unknowns using expert priors
    
    We explore useful tips to be objective in analysis as well as common pitfalls of priors. 

### PyMC3

* [**Prologue:**](http://nbviewer.jupyter.org/urls/raw.github.com/CamDavidsonPilon/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/master/Prologue/Prologue.ipynb) Why we do it.

* [**Chapter 1: Introduction to Bayesian Methods**](http://nbviewer.jupyter.org/urls/raw.github.com/CamDavidsonPilon/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/master/Chapter1_Introduction/Ch1_Introduction_PyMC3.ipynb)
    Introduction to the philosophy and practice of Bayesian methods and answering the question, "What is probabilistic programming?" Examples include:
    - Inferring human behaviour changes from text message rates
    
* [**Chapter 2: A little more on PyMC**](http://nbviewer.jupyter.org/urls/raw.github.com/CamDavidsonPilon/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/master/Chapter2_MorePyMC/Ch2_MorePyMC_PyMC3.ipynb)
    We explore modeling Bayesian problems using Python's PyMC library through examples. How do we create Bayesian models? Examples include:
    - Detecting the frequency of cheating students, while avoiding liars
    - Calculating probabilities of the Challenger space-shuttle disaster
    
* [**Chapter 3: Opening the Black Box of MCMC**](http://nbviewer.jupyter.org/urls/raw.github.com/CamDavidsonPilon/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/master/Chapter3_MCMC/Ch3_IntroMCMC_PyMC3.ipynb)
    We discuss how MCMC operates and diagnostic tools. Examples include:
    - Bayesian clustering with mixture models
    
* [**Chapter 4: The Greatest Theorem Never Told**](http://nbviewer.jupyter.org/urls/raw.github.com/CamDavidsonPilon/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/master/Chapter4_TheGreatestTheoremNeverTold/Ch4_LawOfLargeNumbers_PyMC3.ipynb)
    We explore an incredibly useful, and dangerous, theorem: The Law of Large Numbers. Examples include:
    - Exploring a Kaggle dataset and the pitfalls of naive analysis
    - How to sort Reddit comments from best to worst (not as easy as you think)
    
* [**Chapter 5: Would you rather lose an arm or a leg?**](http://nbviewer.jupyter.org/urls/raw.github.com/CamDavidsonPilon/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/master/Chapter5_LossFunctions/Ch5_LossFunctions_PyMC3.ipynb)
    The introduction of loss functions and their (awesome) use in Bayesian methods.  Examples include:
    - Solving the *Price is Right*'s Showdown
    - Optimizing financial predictions
    - Winning solution to the Kaggle Dark World's competition
    
* [**Chapter 6: Getting our *prior*-ities straight**](http://nbviewer.jupyter.org/urls/raw.github.com/CamDavidsonPilon/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/master/Chapter6_Priorities/Ch6_Priors_PyMC3.ipynb)
    Probably the most important chapter. We draw on expert opinions to answer questions. Examples include:
    - Multi-Armed Bandits and the Bayesian Bandit solution.
    - What is the relationship between data sample size and prior?
    - Estimating financial unknowns using expert priors
    
    We explore useful tips to be objective in analysis as well as common pitfalls of priors. 



    
**More questions about PyMC?**
Please post your modeling, convergence, or any other PyMC question on [cross-validated](http://stats.stackexchange.com/), the statistics stack-exchange.
    
    
Using the book
-------

The book can be read in three different ways, starting from most recommended to least recommended: 

1. The most recommended option is to clone the repository to download the .ipynb files to your local machine. If you have Jupyter installed, you can view the 
chapters in your browser *plus* edit and run the code provided (and try some practice questions). This is the preferred option to read
this book, though it comes with some dependencies. 
    -  Jupyter is a requirement to view the ipynb files. It can be downloaded [here](http://jupyter.org/). Jupyter notebooks can be run by `(your-virtualenv) ~/path/to/the/book/Chapter1_Introduction $ jupyter notebook`
    -  For Linux users, you should not have a problem installing NumPy, SciPy, Matplotlib and PyMC. For Windows users, check out [pre-compiled versions](http://www.lfd.uci.edu/~gohlke/pythonlibs/) if you have difficulty. 
    -  In the styles/ directory are a number of files (.matplotlirc) that used to make things pretty. These are not only designed for the book, but they offer many improvements over the default settings of matplotlib.
2. The second, preferred, option is to use the nbviewer.jupyter.org site, which display Jupyter notebooks in the browser ([example](http://nbviewer.jupyter.org/urls/raw.github.com/CamDavidsonPilon/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/master/Chapter1_Introduction/Ch1_Introduction_PyMC2.ipynb)).
The contents are updated synchronously as commits are made to the book. You can use the Contents section above to link to the chapters.
 
3. PDFs are the least-preferred method to read the book, as PDFs are static and non-interactive. If PDFs are desired, they can be created dynamically using the [nbconvert](https://github.com/jupyter/nbconvert) utility.
 

Instalacion y configuracion
------


Si desea ejecutar los portátiles de Jupyter a nivel local, (Opción 1. arriba), deberá instalar lo siguiente:

- Jupyter es un requisito para ver los archivos IPYNB. Se puede descargar [aquí] (http://jupyter.org/install.html)
- Los paquetes necesarios son PYMC, adormecidos, escaptos y matplotlib.
   - Para usuarios de Linux / OSX, no debe tener un problema al instalar lo anterior, [* excepto MATPLOTLIB en OSX *] (http://www.penandpants.com/2012/2012/02/24/Install-python/).
   - Para los usuarios de Windows, consulte [Versiones pre-compiladas] (http://www.lfd.uci.edu/~gohlke/pythonlibs/) Si tiene dificultades.
   - También se recomienda, para los ejercicios de minería de datos, son [PRAW] (https://github.com/praw-dev/praw) y [solicitudes] (https://github.com/kennethreitz/requests).
- ¿Nuevo en Python o Jupyter, y ayuda con los espacios de nombres? Echa un vistazo a [esta respuesta] (http://stackoverflow.com/questions/12987624/confusion-between-numpy-scipy-matplotlib-and-pylab).

- En los estilos / directorio son una serie de archivos que se personalizan para el cuaderno.
Estos no solo están diseñados para el libro, sino que ofrecen muchas mejoras sobre el
Configuración predeterminada de MATPLOTLIB y el portátil JUPYTER. El estilo de cuaderno no se ha finalizado todavía.



Desarrollo
------

Este libro tiene un diseño de desarrollo inusual. El contenido es de origen abierto, lo que significa que cualquiera puede ser un autor.
Los autores envían contenido o revisiones utilizando la interfaz GitHub.

### Cómo contribuir

#### ¿Qué contribuir?

- La lista actual del capítulo no se finaliza. Si ve algo que falta (MCMC, mapa, redes bayesianas, buenas opciones previas, clases potenciales, etc.),
Siéntase libre de comenzar allí.
- limpiando el código de Python y haciendo código más PYMC-ESQUE
- Dando mejores explicaciones.
- Errores de ortografía / gramática
- Sugerencias
- Contribuyendo a los estilos de cuadernos Jupyter.


#### commitiendo

- Todos los comisiones son bienvenidos, incluso si son menores;)
- Si no está familiarizado con GitHub, puede enviarme un correo electrónico a las contribuciones al correo electrónico a continuación.

Comentarios
------
* Estos son satíricos, pero real *

"No, pero se ve bien" - [John D. Cook] (https://twitter.com/johndcook/status/359672133695184896)

"Yo ... Lea este libro ... ¡Me gusta!" - [Andrew Gelman] (http://www.andrewgelman.com/2013/07/21/Bayes-Related)

"¡Este libro es una bendición, y una refutación directa a esa 'HMPH! ¡No conoces a Matemáticas, meablos!' escuela de pensamiento...
El modelo de publicación es tan inusual. No solo está abierto, sino que se basa en solicitudes de tracción de cualquier persona para progresar el libro. Esto es ingenioso y alentador "- [Usuario excitado de Reddit] (http://www.reddit.com/r/python/comments/1alnal/probababilist_programming_and_bayesian_methods/)



Contribuciones y gracias
-----


Gracias a todos nuestros autores contribuyentes, incluyendo (en orden cronológico):

Authors | | | |
--- | --- | --- | ---
[Cameron Davidson-Pilon](http://www.camdp.com) |  [Stef Gibson](http://stefgibson.com) | [Vincent Ohprecio](http://bigsnarf.wordpress.com/) |[Lars Buitinck](https://github.com/larsman)
[Paul Magwene](http://github.com/pmagwene) |  [Matthias Bussonnier](https://github.com/Carreau) | [Jens Rantil](https://github.com/JensRantil) |  [y-p](https://github.com/y-p)
[Ethan Brown](http://www.etano.net/) |  [Jonathan Whitmore](http://jonathanwhitmore.com/) | [Mattia Rigotti](https://github.com/matrig) |  [Colby Lemon](https://github.com/colibius)
[Gustav W Delius](https://github.com/gustavdelius) |  [Matthew Conlen](http://www.mathisonian.com/)  | [Jim Radford](https://github.com/radford) |  [Vannessa Sabino](http://baniverso.com/)
[Thomas Bratt](https://github.com/thomasbratt) |  [Nisan Haramati](https://github.com/nisanharamati) |  [Robert Grant](https://github.com/bgrant) | [Matthew Wampler-Doty](https://github.com/xcthulhu)
[Yaroslav Halchenko](https://github.com/yarikoptic) |  [Alex Garel](https://github.com/alexgarel) | [Oleksandr Lysenko](https://twitter.com/sash_ko) |  [liori](https://github.com/liori)
[ducky427](https://github.com/ducky427) |  [Pablo de Oliveira Castro](https://github.com/pablooliveira) | [sergeyfogelson](https://github.com/sergeyfogelson) |  [Mattia Rigotti](http://neurotheory.columbia.edu/~mrigotti/)
[Matt Bauman](https://github.com/mbauman) | [Andrew Duberstein](http://www.andrewduberstein.com/) | [Carsten Brandt](http://cebe.cc/) |  [Bob Jansen](http://web2docx.com)
 [ugurthemaster](https://github.com/ugurthemaster)   | [William Scott](https://github.com/williamscott)   |  [Min RK](http://twitter.com/minrk)  |  [Bulwersator](https://github.com/Bulwersator)
  [elpres](https://github.com/elpres)  |  [Augusto Hack](https://github.com/hackaugusto)  | [Michael Feldmann](https://github.com/michaf)   | [Youki](https://github.com/Youki)
   [Jens Rantil](http://jensrantil.github.io) |  [Kyle Meyer](http://kyleam.com)  |  [Eric Martin](http://ericmart.in)  | [Inconditus](https://github.com/Inconditus)
 [Kleptine](https://github.com/Kleptine)   |  [Stuart Layton](https://github.com/slayton)  |  [Antonino Ingargiola](https://github.com/tritemio)  |  [vsl9](https://github.com/vsl9)
  [Tom Christie](https://github.com/tom-christie)  |  [bclow](https://github.com/bclow)  |  [Simon Potter](http://sjp.co.nz/)  | [Garth Snyder](https://github.com/GarthSnyder)
 [Daniel Beauchamp](http://twitter.com/pushmatrix)  |  [Philipp Singer](http://www.philippsinger.info)  | [gbenmartin](https://github.com/gbenmartin) | [Peadar Coyle](https://twitter.com/Springcoil)
Nos gustaría agradecer a la comunidad de Python para construir una arquitectura increíble.Nos gustaría agradecer al
Comunidad de estadísticas para construir una arquitectura increíble.

De manera similar, el libro solo es posible debido a la biblioteca [PYMC] (http://github.com/pymc-devs/pymc).Un gran agradecimiento a los centros de PyMC: Chris Fonnesbeck, Anand Patil, David Huard y John Salvatier.

Una última gracias.Este libro fue generado por Jupyter Notebook, una maravillosa herramienta para desarrollar en Python.Agradecemos al Ipython / Jupyter
Comunidad para desarrollar la interfaz portátil.Todos los archivos de portátiles Jupyter están disponibles para su descarga en el repositorio de GitHub.



#### Contacto
Póngase en contacto con el autor principal, CAM DAVIDSON-PILON en cam.davidson.pilon@gmail.com o [@cmrndp] (https://twitter.com/cmrn_dp)

![Imgur](http://i.imgur.com/Zb79QZb.png)
