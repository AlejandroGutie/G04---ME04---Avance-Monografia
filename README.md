# Seminario de Analítica y Ciencia de Datos
### ME04 Avance de Monografía
## _Aplicación de Ciencia de datos sobre la desnutrición e inseguridad alimentaria en los municipios de Antioquia en el marco del segundo Objetivo de Desarrollo Sostenible, 2013 - 2022_

**Grupo 04**\
Huberth Rolando Hincapié Arango\
Yeisson Alejandro Gutiérrez Cano

# Repositorio
El contenido y anexos como insumo y producto del desarrollo del avance en la monografía, reposan en el siguiente enlace de [GitHub.](https://github.com/AlejandroGutie/G04-ME04-Avance-Monografia/tree/main)

# Procesamiento de los datos
Se llevó a cabo en la herramienta de Google Collaboratory, en el siguiente enlace al Notebook denominado ["ME04 Desnutrición e inseguridad alimentaria".](https://colab.research.google.com/drive/1M0CyHxjmfsjj9tHoeWcnQvqw33gPURX2?authuser=1#scrollTo=m-Kl9vWJJar_)

## Ejecución Notebook
Se consolida en el notebook el apartado de Herramientas representadas en las Librerías, el Procesamiento de datos realizando su importación representados en dos dataset sobre los indicadores a nivel municipal de la Prevalencia de inseguridad alimentaria en el hogar (moderada o severa) y la Incidencia de desnutrición aguda en población menor de 5 años, e indicadores adicionales de Cobertura en educación superior, Cobertura de viviendas con agua potable y la Cobertura de viviendas con energía eléctrica a nivel municipal.

Se realiza una lectura de las variables contenidas en los dataset, se valida su completitud gráficamente y se lleva a cabo una identificación y selección de variables numéricas y categóricas de interés como primer insumo de variables predictoras del fenómeno de la desnutrición y la inseguridad alimentaria.

Posteriormente se presenta el momento de definición del conjunto de datos, incorporando nuevas instancias con la unión de ambos dataset en uno único de 5500 registros, con la medición de 6 variables numéricas y categóricas con la identificación del municipio y valor de la medición de cada indicador como primer insumo de datos.

Se lleva a cabo la visualización del comportamiento de la magnitud en los registros para cada Indicador, Municipio y el valor de su medición para cada año.

## Definición del conjunto de datos
Se lleva cabo la selección y exportación de las variables definitivas para el conjunto de datos y la unión por columnas de ambos dataset en uno definitivo como primer insumo de datos para el logro definitivo de los objetivos planteados.

# Referencias
***Datos***\
Secretaría Seccional de Salud de Antioquia, “Servicio de Información y Estadística”, 2023.  [Online]. Available: https://dssa.gov.co/inicio-estadisticas

Secretaría Seccional de Salud de Antioquia, “Servicio de Información y Estadística”, 2023.  [Online]. Available: https://dssa.gov.co/estadisticas-vitales
