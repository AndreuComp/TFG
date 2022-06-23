ACCESO A LOS FICHEROS CSV:

https://drive.google.com/drive/folders/1Mq1Bf3zlpmwSFxZNpxPGMSK5dGvm9Ldi?usp=sharing

FICHEROS CSV:

- calendar_sept.csv: Contiene los datos de estatus de cada dia para los pisos de septiembre.
- listings_dec.csv: Contiene los datos de los pisos para el dia 7 de diciembre.
- listings_sept.csv: Contiene los datos de los pisos para el dia 10 de septiembre.
- listing_nt.csv: Contiene la primera base de datos realizada (no tratada).
- df_host_verifications.csv: Contiene la transformación de la variable "host_verifications" a variables binarias.
- df_amenities.csv: Contiene la transformación de la variable "amenities" a variables binarias.
- df_final.csv: Contiene el data frame después de su tratamiento.
- df_modelo.csv: Contiene el data frame con las transformaciones en variables respuesta y eliminacion de variables no útiles para el modelo.

CODIGO EMPLEADO:

- 01 Importación y tratado de la base de datos:

   - 01_01_Importacion_BD.ipynb: Creación de la base de datos inicial a partir de "listing_sept.csv", "listing_dec.csv" y "calendar_sept.csv".
   - 01_02_Preprocessing.ipynb: Tratado de la base de datos: eliminación de variables, tratamiento de NAs, estudio de correlación, etc.

- 02 Analisis descriptivo gráfico de la base de datos:

   - 02_01_Graficos.ipynb: Gráficos para todas las variables después del tratado de la base de datos.
   - 02_02_Heatmaps.ipynb: Mapas de calor para las variables de interés sobre el mapa de Barcelona.

- 03 Selección del modelo óptimo XGBoost y su aplicación

   - 03_01_XGBoost.ipynb: Selección de los hiperparametros y variables optimas para el modelo XGBoost.
   - 03_02_Aplicación_Modelo.ipynb: Conjunto de funciones para una facil manipulación y cálculo del ranking.

GRÁFICOS:

- Graficos float: Contiene los gráficos para las variables númericas.
- Graficos integer: Contiene los gráficos para las variables binarias.
- Graficos category: Contiene los gráficos para las variables categóricas.
- Heatmaps: Contiene los mapas de calor realizados para algunas variables de interés.
