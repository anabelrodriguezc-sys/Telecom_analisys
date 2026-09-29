# Telecom_analisys
- Objetivo. Conocer las conductas en cuanto a servicios móviles, específicamente a llamadas y mensajes de las poblaciones de México y Colombia, identificando la segmentación por edades, las preferencias de uso y los posibles compartamientos atípicos. Esto con el fin de generar estrategias comerciales y de experiencia del usuario.
- 
- Para el análisis se utilizaron 3 datasete, los cueles se enlistana acontinuación:
  1. plans.cv, que contiene la información referente a las carcaterística de los planes (costo, minutos, GB incluidos, costo adicionnal)
  2. users_latam.csv: información de clientes: edad, ciudad, fecha de registro, plan contratado.
  3. usage.csv: el detalle de uso real: llamadas (duración) y mensajes (longitud).

- Etapas. Se realizó un reconocimiento de las bases de datos, de sus columnas, datos nulos y la cantidad de datos con las que contaba sus columnas.  Posteriormente se realizó una limpieza de los datasets, estandarizando datos como fecha y decidiendo si los datos con valores nulos se corregían, eliminaban o conservaban como tal. En este primer momento se identificó un número considerable de valores nulos para duración y longitud, esto debido a que el dato de la columna no podía medirse con ambos factores, por lo cual se decidió conservarlos para evitar un sesgo en el análisis. Asimismo se analizó la estadística de los datos, para identificar si habían comportamientos atípicos u outliers.
En este análisis se tomó la columna user_id como columna de clave, pero conforme se avanzó en el análisis se identificó que los valores no eran coincidentes, lo que mostraba un número de valores nulos altos.
Finalmente, se realizaron gráficos como apoyo visual de lo identificado. 
-
- El presente deberá abrirse Google Colab),  

Se comparten las bases 
/datasets/plans.csv
/datasets/users_latam.csv
/datasets/usage.csv

Se cargaron las bibliotecas pandas, seaborn, matplotlib.pyplot y numpy. 
