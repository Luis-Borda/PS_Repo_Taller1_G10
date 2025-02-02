# Problem Set 1: Predicting Income

## Universidad de Los Andes - Maestría en Economía Aplicada

Integrantes:

Luis Olegario Borda Silva

Julian Santiago Muñoz Garrido

Joan Sebastián Potosí Hoyos

Juan Felipe Vargas Guacheta

# Introducción

La evasión tributaria es uno de los principales fenómenos sociales que encienden las alarmas del Estado colombiano, pues no sólo refleja un amplio canal de fuga de recursos públicos sino que además, muestra la poca eficiencia institucional en los programas de fiscalización. Al respecto, se estima que la evasión fiscal estaría quitando al Estado cerca de $65 billones anuales, es decir 5.4 puntos del PIB (DIAN, 2022). Cabe resaltar que entre los tributos que más se pierden recursos por evasión estan el impuesto a la renta y el IVA. 

Bajo este contexto, el desarrollo de análisis precisos sobre los ingresos de las personas es crucial, ya que permite detectar casos de fraude fiscal y diseñar herramientas de política pública para mitigar sus impactos en la adimistración tributaria. En este orden de ideas, en el presente problem set, se estructura un modelo de predicción del ingreso de los hogares en Colombia para el año 2018, utilizando como fuente de información la Gran Encuesta Integrada de Hogares (GEIH). Para realizar este ejercicio se aplicaron los conceptos aprendidos en el curso "Big data y Machine Learning para economía aplicada" de la Universidad de los Andes.

# Contenido del repositorio

## Document
En esta carpeta se encuentra el documento en el cual se desarrollo el problem set. El documento inicia con corta introducción, posteriormente en la segunda sección, se hace una descripción de los datos utilizados incluyendo información relevante sobre la GEIH, el proceso de obtención y limpieza de los datos y algunas estadísticas descriptivas de las variables utilizadas. Luego, en la sección 3 se presenta un análisis de la relación edad salario, sobre el entendido que los salarios tienden a ser bajos cuando el trabajador es joven e incrementan a medida que envejece. En la sección 4, se hace un análisis de la brecha salarial por genero, presentando las estimaciones obtenidas y discutiendo los resultados a la luz de los modelos planteados. Finalmente, en la sección 5, se hace una predicción de las ganancias haciendo uso de 5 modelos con diferentes niveles de complejidad y se compara su desempeño predictivo en terminos del MSE.

## Scripts

En esta carpeta se encuentran los scripts estructurados para desarrollar el problem set organizados de la siguiente manera:

- `Punto 2 - descriptivas`: Aquí se encuentra el código utilizado para hacer el web scraping y consolidar la base de datos. Además, contiene el análisis descriptivo de las variables a utilizar.
- `Punto 2 - Datos Faltantes`: En este script se encuentra el proceso utilizado para la imputación de datos a partir de una regresión estocástica.
- `Punto 3`: Aquí se estima el perfil de edad-salario de los individuos de la muestra que da respuesta al punto 3 del problem set.
- `Punto 4`: En este script se estima la brecha de ingresos por genero que da respuesta al punto 4 del problem set.
- `Punto 5`: Aquí se encuentra el código utilizado para realizar la predicción de ganancias de los diferentes modelos y evalúa su poder predictivo.

## Stores

En esta carpeta se aloja la base de datos utilizada para realizar el problem set. Para este caso particular, la información proviene de la GEIH la cual proporciona información estadística sobre el tamaño y estructura de la fuerza de trabajo (empleo, desempleo y población fuera de la fuerza de trabajo), los ingresos laborales y no laborales de los hogares, la pobreza monetaria y la pobreza monetaria extrema de la población residente en el país​.  

## Views

En esta carpeta se encuentran las gráficas en formato JPG y las tablas con algunos de los resultados.




