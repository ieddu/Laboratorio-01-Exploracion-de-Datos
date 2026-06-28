# Laboratorio 01 - Exploración de Datos

Objetivos: Analizar los tres conjuntos de datos almacenados en las bases de datos MySQL que estoy corriendo, utilizando Docker, las bases de datos se llaman:
`pia_data_01`, `pia_data_02` y `pia_data_03` (todas con la tabla `salaries`),
alojadas en el entorno de docker compose, para detectar problemas comunes
de calidad de datos:

1. Datos faltantes (*Missing Data*)
2. Problemas de escala (*Scaling Issues*)
3. Clases desbalanceadas (*Imbalanced Classes*)
4. Valores anómalos (*Outliers*)
5. Problemas de formato
6. Problemas de estandarización

Adicionalmente he analizado la distribución de cada variable para identificar patrones, sesgos y particularidades (formas de la distribución, mezcla de distribuciones, etc.). Este análisis lo realice en un notebook llamado Laboratorio 01-Exploración de Datos.ipynb y el informe detallado con los hallazgos obtenidos por cada una de las características del dataset se presentan a continuación.