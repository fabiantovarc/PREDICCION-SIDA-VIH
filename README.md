# PREDICCION-SIDA-VIH
# Proyecto Data Mining 
****
**Universidad Externado de Colombia**

**Ciencia de Datos**

**Data Mining**

![image](https://github.com/user-attachments/assets/4f1c3f1d-dede-4bea-8eea-9d70e2b16c00)

Velu, A. (2023). AIDS virus infection prediction [Conjunto de datos]. Kaggle. https://www.kaggle.com/datasets/aadarshvelu/aids-virus-infection-prediction/data

**Propósitos:**

* Poner en práctica los métodos de `Python` estudiados.

* Usar los conceptos estudiados para revelar información en una data set.

* Identificar el contexto y alguna oportunidad de negocios asociadas a una data set.

* Poner en práctica la redacción de secciones específicas de un proyecto.


# 2. Contextualización y problema
****

##  2.1. Contexto de la base de datos:
Este dataset proviene de un estudio **clínico** realizado en la década de **1990**, diseñado para investigar y comprender mejor la progresión del **SIDA** en pacientes que recibieron diferentes tipos de tratamientos **antirretrovirales**. Los datos fueron recolectados para analizar cómo diversos factores personales, históricos y médicos influyen en la probabilidad de infección y en la **progresión** de la enfermedad.

La base de datos incluye información detallada sobre el tiempo hasta un evento crítico o la censura de los pacientes, así como múltiples variables relacionadas con la demografía, el historial médico, el tipo de tratamiento recibido, y los resultados de laboratorio. Entre estas variables se encuentran la edad, el peso, la raza, el género, la actividad sexual, el historial de uso de drogas intravenosas, el estado funcional medido por la **escala de Karnofsky**, y varios indicadores de tratamientos y síntomas.

El objetivo principal de este conjunto de datos es proporcionar a los investigadores un recurso para estudiar la efectividad de diferentes regímenes de tratamiento, entender los factores de riesgo asociados con la infección por el virus del SIDA, y desarrollar modelos predictivos que puedan ayudar a personalizar el tratamiento y mejorar los resultados en pacientes con VIH/SIDA.

¿Qué representan las instancias de este conjunto de datos?.
- Registros sanitarios
- Pacientes con SIDA
- Sólo EE.UU.

## 2.2. Descripción del problema
El VIH/SIDA sigue siendo una de las enfermedades más críticas en salud pública a nivel mundial, debido a sus devastadoras consecuencias sobre el sistema inmunológico. El diagnóstico oportuno y la predicción de su progresión son fundamentales para mejorar la calidad de vida de las personas afectadas. No obstante, existen múltiples variables clínicas y demográficas que podrían influir en el diagnóstico y la evolución de la enfermedad, por lo que resulta esencial identificar cuáles de ellas son clave para mejorar el manejo y tratamiento de la infección.

Entre estas variables, la ausencia de ciertos glóbulos blancos, como los CD40, podría estar estrechamente relacionada con el diagnóstico de SIDA, ya que este tipo de células desempeña un papel crucial en la respuesta inmune. Además, la escala de Karnofsky, que mide el estado funcional del paciente, podría proporcionar información adicional en conjunto con otras variables para predecir la infección por VIH/SIDA.

Asimismo, las características demográficas como la orientación sexual (homo) y el género pueden influir en el conteo de células CD4, un biomarcador clave en la progresión del VIH, lo cual hace necesario analizar su impacto en el estado de salud de los pacientes.
