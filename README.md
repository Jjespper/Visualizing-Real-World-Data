# Proyecto Geolocalización


El objetivo de este proyecto es encontrar la mejor ubicación para situar una empresa que se dedica al sector de los videojuegos.

En el repositorio encontrarás dos Jupyter Notebooks y una carpeta con la base de datos que se ha trabajado despues del primer Jupyter Notebook.

En el Jupyter Notebook llamado "Primera limpieza Pandas" se realiza una selección, filtrado y limpieza de la base de datos con la que va a trabajar posteriormente.

En el segundo Jupyter Notebook "2. geoQuery + API" se realizan geoqueries para tratar de encontrar la mejor localización.

Las condiciones a las que yo he datoado de mayor valor para la toma de decisión son las siguientes:

-  Localizaciones donde existiese una red potencial de networking para poder establecer posibles futuros vínculos. 

-  Localizaciones donde existan opciones de ocio, en este caso utilizando la API de Google busco localizaciones donde existan bares y clubs.

-  Y por último la comodidad que ofrecen establecimientos donde se puede comprar comida recien hecha para llevar también ha sido considerado como un valor añadido a la localización a encontrar. 

He categorizado por empresas de videojuegos o empresas tecnológicas (en general), dándole más valor a las empresas de videojuegos, ya que es el sector específico de la empresa.

Tras considerar todas esta condiciones se ha realizado un ranking, y la localización con la mejor puntuación ha sido la finalmente elegida. Esta localización la puede encontrar al final del segundo Jupyter Notebook, la representación se ha realizado con la librería Follium.



**Futuras mejoras:_**
Hacer una categorización de sectores de actividad de las empresas y utilizarlas para el ranking de empresas cercanas en el radio establecido. 
