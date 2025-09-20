# 🚕 Preferencias de pasajeros en taxis en el mercado de viajes compartidos
Análisis de los datos de viajes de taxis en Chicago durante noviembre de 2017 para identificar patrones de demanda, desempeño de las compañías de taxis y factores que afectan la duración de los viajes.

## 📄 Descripción del proyecto
En este proyecto abordaremos un caso de estudio para la empresa Zuber, una nueva empresa de viajes compartidos que se está lanzando en Chicago, realizaremos un análisis exploratorio donde podremos obtener información acerca del estado del arte para el negocio de taxis, dentro de los datasets que estudiaremos, contamos con información como ; Flujo de viajes de las empresas prestadoras de servicios de taxi, información sobre el estado del tiempo (clima) conforme a los viajes realizados, la duración y destino de los mismos, así como la cantidad de viajes realizados para cada destino.

## 🎯 Objetivos del proyecto
El objetivo de este análisis es poder contar con información y conclusiones suficientes acerca de las preferencias de los pasajeros, el impacto de los factores externos en los viajes, así como el flujo que mantienen nuestros competidores actuales. Todo lo anterior enfocado a la creación de estrategias que nos permitan tener un ingreso exitoso al mercado y priorizar la eficiencia de recursos (humanos y económicos) para llevar a cabo nuestra estrategia de mercado.

## 🛠 Etapas de finalización del proyecto
Analizaremos los datos almacenados en el archivo `games.csv`. Aunque tenemos cierta información preliminar sobre los datos, necesitamos evaluar su calidad.

Nuestro análisis implicará varias etapas:

1. 📊 Descripción inicial de los datos: Proporcionaremos una breve descripción general de los datos, incluida la información general y las estadísticas clave.
2. 🔧 Preprocesamiento de los datos: Mejoraremos la calidad de los datos realizando tareas como leer y validar los datos, cambiar el nombre de las columnas, manejar los valores faltantes, ajustar los tipos de datos y crear nuevas columnas relevantes.
3. 🔍 Análisis exploratorio de datos: Exploraremos los datos para descubrir patrones y conocimientos relacionados con el rendimiento de las ventas de videojuegos. Presentaremos nuestros hallazgos, conocimientos y recomendaciones.
4. 📈 Análisis estadístico de los datos: Realizaremos pruebas estadísticas para examinar dos hipótesis aceptadas.
5. 📝Conclusión: Resumiremos los resultados de nuestro análisis y proporcionaremos conclusiones generales.

A lo largo de estas etapas, nos aseguraremos de realizar un análisis integral de los datos para obtener información valiosa sobre las ventas de videojuegos.

## 📊 Descripción de los datos

Previamente se realizó una consulta de datos mediante queries a la base de datos (PostgreSQL) y obtuvimos los siguientes datasets:

**/datasets/project_sql_result_01.csv. contiene los siguientes datos:**
* <code>company_name</code>: nombre de la empresa de taxis
* <code>trips_amount</code>: el número de viajes de cada compañía de taxis el 15 y 16 de noviembre de 2017. 

**/datasets/project_sql_result_04.csv. contiene los siguientes datos:**
* <code>dropoff_location_name</code>: barrios de Chicago donde finalizaron los viajes
* <code>average_trips</code>: el promedio de viajes que terminaron en cada barrio en noviembre de 2017.

**/datasets/project_sql_result_07.csv — el resultado de la última consulta. Contiene datos sobre viajes desde el Loop hasta el Aeropuerto Internacional O'Hare. Recuerda, estos son los valores de campo de la tabla:**
* <code>start_ts</code>: fecha y hora de la recogida
* <code>weather_conditions</code>: condiciones climáticas en el momento en el que comenzó el viaje
* <code>duration_seconds</code>: duración del viaje en segundos
  
## 📚 Librerías 
- Pandas
- NumPy
- matplotlib
- seaborn
- Scipy

## ⚖️ Licencia
Este proyecto está bajo la licencia Creative Commons Attribution-NonCommercial 4.0 International Public License (CC BY-NC 4.0). Eres libre de usar, compartir y adaptar este trabajo para fines no comerciales, siempre que se dé el crédito adecuado. Para más detalles, consulta el archivo [LICENCIA](LICENCIA.txt) o visita [Creative Commons](https://creativecommons.org/licenses/by-nc/4.0/).
