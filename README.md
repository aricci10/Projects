Carpeta con diferentes proyectos en los que he trabajado. Estos son:

# Tesis física

Éste es quizás el más importante. Consistía en realizar tomografía de estados cuánticos a qubits preparados en polarización y camino en fotones. En términos clásicos esto era como crear diferentes bolsas con bolas y cubos de colores, posteriormente sacando de un elemento de la bolsa a la vez y realizando las estadísticas se
debía clasificar qué había en la bolsa. En mi proyecto, esta bolsa eran los estados de polarizacion y camino en fotones. La tomografía de estados cuánticos es el equivalente a sacar un elemento a la vez, devolverlo y a partir de esta estadística reconstruir lo que hay en la bolsa.

El procesamiento lo realicé todo en los notebooks que están en la carpeta. A partir de millones de datos tocaba reconstruir las esferas que se obervan ahi. De ahí rescataría path_tomo y path_pol_tomo como los más relevantes. MUB son una serie de cálculos. 

# EMNIST

Emnist fue mi primer proyecto usando NN. Consistía en realizar classificar caracteres del Extended-MNIST, variando diferentes parámetros. De base usé 3 "hidden-layers" con 100 unidades ReLU cada una. Sobre esta base, probé diferentes técnicas de gradientes adaptativos, como RMSProp y ADAM. Luego usé un Cosine Scheduler para cambiar el "learning rate". Finalmente probé regularización con L2 y con "weight decay" sobre ADAM. Todo esto lo hice sobre una librería que nosotros mismos hemos ido construyendo a lo largo del curso que se llama MLP y es un estilo de Pytorch basado en Numpy. https://github.com/CSTR-Edinburgh/mlpractical. De acá vale la pena mirar el documento ya que el notebook tiene muchísimas cosas, debido a que iba experimentando ahí, entonces no está muy ordenado. 

# Tesis IELE

Consistió en la creación de un medidor de potencia eléctrica mediante el efecto de Magneto-Resistencia Gigante. Acá usé python para crear una interfaz de usuario que se comunicaba mediante TCP con una Raspberry Pi y mostraba la medición en tiempo real. Acá quiero hacer enfásis en que no sabía mucho de python en este ámbito (lo había usado mucho en programación científica, pero no en OOP/interfaces), y básicamente saqué el proyecto de ceros sin ayuda. Estaba trabajando con un tema que no es parte de ningún grupo de investigación en la U, entonces me tocó todo por mi cuenta. Por razones de derechos de autor con la U no puedo publicar el código. 

# MC 

Métodos computacionales (MC) es una materia de física que vi en el 2015. De ahí subo los trabajos más interesantes. HW5 Era acerca de simulaciones de 3 y 4 cuerpos bajo efectos gravitacionales entre ellos. Ahí hay unas animaciones bien interesantes. Proyecto final fue un intento de animar una guitarra, basada en sonidos de audio que le poníamos. 

# MLPR

Una tarea reciente de ML, enfocado a predicción en audio, usando diferentes técnicas. 

# DSP 

Implementamos un procesador de señales digitales en C, para diferentes efectos de audio en vivo. 

# Taller de potencia 

Lo subo porque en este proyecto me encargé de la parte de la porgramación de  una funcion de protección para análisis de fallas en sistemas eléctricos, usando MATLAB/simulink. De ahí básicamente mis compañeros me entregaban un archivo con una serie de datos y mi programa se encargaba de detectar el tipo de falla. 

