
# Spark, Pyspark y SparkSQÑ

Spark es usado actualmente como una herramienta de procesamiento de datos en procesos de big data. Normalmente, se tienn multiples fuentes con datos. Y por lo general se quiere crear un proceso de ETL o ELT a un data warehouse o un datalake.

En python existen 3 librerias populares para la transaformación de datos, pandas, dask y pyspark. 

* Pandas -  Es la libreria convencional para manejo de datos.
* Dask - Es una libreria que busca la paralelización de pandas, permitiendo tranajar en cluster de procesamiento.
* Pyspark - Es el framwrok de Spark para python.

## Arquitectura de spark

* **Drivers:** Son los nodos usados para someter el trabajo.
* **Masters:** Son usados para administrar el cluster.
* **Workers** Hacen el trabajo.

# SPARK SQL

En SparkSQL aplican todas la misma sintaxis que se usa en SQL. Si se usa Databrick es tan sencillo como usar el magic, cargar las tablas y luego usar sentencias SQL para procesar y unir los datos.
