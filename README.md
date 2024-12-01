# Acerca de mí

Economista y financiera certificada en análisis de datos con sólida experiencia en extracción, limpieza y modelado de datos estratégicos. 

Genero insights accionables que optimizan procesos y apoyan la toma de decisiones estratégicas, logrando ahorros significativos de tiempo mediante la automatización.

### Habilidades tecnológicas
- Análisis y gestión de datos utilizando **Excel / SQL / Python / R**
- Visualización de datos y narración de historias usando **Tableau**

### Habilidades blandas
Análisis de datos | Resolución de problemas | Comunicación efectiva | Trabajo en equipo | Orientación a resultados | Organización | Proactividad | Atención al detalle | Optimización de Procesos

<!-- PARA HACER QUE EL LINK ABRA EN OTRA PESTAÑA
<a href="https://www.linkedin.com/in/marielalegoma/" target="_blank">
  <img src="https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
</a>-->
[![LinkedIn](https://img.shields.io/badge/linkedin-%23295F98.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/marielalegoma/)
[![Outlook](https://img.shields.io/badge/Microsoft_Outlook-295F98?style=for-the-badge&logo=microsoft-outlook&logoColor=white)](mailto:mariel_goma@outlook.com)

* * *

# Proyectos seleccionados

## Análisis de retención de clientes para gimnasio
En todas las industrias, la retención de clientes es fundamental para garantizar **ingresos sostenibles** y **reducir los costos asociados con la adquisición de nuevos clientes**. Identificar los factores clave que influyen en la retención y cancelación permite al gimnasio Model Fitness anticiparse a los riesgos de abandono, **diseñar estrategias de fidelización efectivas** y **personalizar las experiencias para cada cliente**.

#### Herramientas y tipo de proyecto
![Python](https://img.shields.io/badge/python-357ebd?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23357ebd.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-357ebd?style=for-the-badge)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23357ebd.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Limpieza de datos](https://img.shields.io/badge/Limpieza_de_datos-295F98?style=for-the-badge)
![Transformación de datos](https://img.shields.io/badge/Transformación_de_datos-295F98?style=for-the-badge)
![Análisis de datos](https://img.shields.io/badge/Análisis_de_datos-295F98?style=for-the-badge)
![Modelos de predicción](https://img.shields.io/badge/Modelos_de_predicción-295F98?style=for-the-badge)

### Metodología
- **Preprocesamiento de datos:** Se limpiaron y estandarizaron los datos, eliminando inconsistencias y verificando la ausencia de duplicados y valores faltantes.
- **Explorartory Data Analysis (EDA):** Se analizaron características demográficas y de uso, identificando patrones en clientes que permanecen y los que cancelan.
- **Modelado predictivo:** Se entrenaron modelos de regresión logística y bosque aleatorio para predecir la cancelación de clientes con un precisión del 85% y 84%, respectivamente.
- **Clustering:** Se segmentaron los clientes en grupos utilizando K-means para identificar comportamientos similares.

### Preguntas clave
1. ¿Qué factores demográficos o de comportamiento influyen más en la cancelación?
2. ¿Qué características diferencian a los clientes leales de los que abandonan?
3. ¿Cómo se pueden segmentar los clientes para diseñar estrategias personalizadas?

### Conclusiones y recomendaciones

#### Factores críticos de retención:
- La proximidad al gimnasio, contratos más largos, la participación en sesiones grupales y mayor frecuencia de visitas están fuertemente asociados con una menor tasa de cancelación.
- Clientes jóvenes, con contratos cortos y baja frecuencia de visitas, tienen mayores tasas de cancelación.

#### Estrategias recomendadas:
- **Extender contratos cortos:** Ofrecer incentivos para ampliar contratos de 1 mes.
- **Promover actividades grupales:** Diseñar campañas que destaquen los beneficios de participar en sesiones grupales.
- **Campañas personalizadas:** Utilizar el modelo predictivo para identificar clientes en riesgo y ofrecer promociones específicas.
- **Segmentación proactiva:** Clasificar clientes nuevos por edad y duración de contrato para diseñar estrategias de retención desde el inicio.

### Visualizaciones destacadas
1. **Distribución de cancelación según duración del contrato:** Observamos que quienes cancelaron suelen contratar en su mayoría 1 mes, al igual que quienes no cancelan. Sin embargo, quienes permanecen suelen también contratar por periodos de 1 año y 6 meses, mientras que los que cancelan en su minoría contratan en dichos periodos.
![Contract Period Histogram](/assets/img/p01_contract_period_histogram.png)
2. **Matriz de correlaciones:** Se encontró que Las características `month_to_end_contract` y `contract_period` están altamente correlacionadas (0.9), lo que sugiere que se debe tener cuidado con la multicolinealidad al desarrollar modelos predictivos.
![Corr Matrix Churn Data](/assets/img/p01_gym_churn_corr.png)
3. **Análisis de clústeres:** El dendrograma muestran cómo los clientes se agrupan en segmentos distintos basados en sus características, donde el número óptimo de clústeres sugerido es 4.
![Dendrogram](/assets/img/p01_dendrogram.png)

**Explora más detalles del proyecto en el [repositorio completo](https://github.com/MaleGoma/customer-retention-analysis).**

## Análisis de ventas de videojuegos
Este proyecto analiza las ventas de videojuegos por región, plataforma y género para identificar patrones clave que permitan a la tienda online Ice **detectar proyectos prometedores** y **planificar campañas publicitarias efectivas**. Al entender las dinámicas de mercado en Norteamérica, Europa y Japón, se busca **optimizar estrategias de marketing** y **maximizar el retorno de inversión en los títulos más prometedores**.

#### Herramientas y tipo de proyecto
![Python](https://img.shields.io/badge/python-357ebd?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23357ebd.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23357ebd.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![Seaborn](https://img.shields.io/badge/Seaborn-357ebd?style=for-the-badge)
![SciPy](https://img.shields.io/badge/SciPy-%23357ebd.svg?style=for-the-badge&logo=scipy&logoColor=white)
![Limpieza de datos](https://img.shields.io/badge/Limpieza_de_datos-295F98?style=for-the-badge)
![Transformación de datos](https://img.shields.io/badge/Transformación_de_datos-295F98?style=for-the-badge)
![Análisis de datos](https://img.shields.io/badge/Análisis_de_datos-295F98?style=for-the-badge)
![Pruebas de hipótesis](https://img.shields.io/badge/Pruebas_de_hipótesis-295F98?style=for-the-badge)
![Visualización de datos](https://img.shields.io/badge/Visualización_de_datos-295F98?style=for-the-badge)

### Metodología
- **Preprocesamiento de datos:** Limpieza de datos (valores ausentes, duplicados, formatos de columnas, y tipos de datos adecuados).
- **Análisis exploratorio de datos:** Identificación de las plataformas y géneros más populares y evaluación de la correlación entre puntuaciones de usuarios/críticos y ventas.
- **Segmentación regional:** Comparación de preferencias por plataformas y géneros en Norteamérica, Europa y Japón.
- **Pruebas de hipótesis:** Comparación de calificaciones promedio entre plataformas y géneros.

### Preguntas clave
1. ¿Cuáles son las plataformas con mayores ventas globales y cómo varían estas por región?
2. ¿Qué géneros de videojuegos son más populares en Norteamérica, Europa y Japón?
3. ¿Qué relación existe entre las puntuaciones de usuarios/críticos y las ventas globales de videojuegos?
4. ¿Existen diferencias significativas en las calificaciones promedio entre plataformas y géneros?

### Conclusiones y recomendaciones
#### Dinámica de ventas por región:
- Norteamérica y Europa prefieren juegos de acción y disparos en consolas como Xbox y PlayStation.
- Japón, en cambio, favorece juegos de rol en plataformas portátiles como Nintendo 3DS.

#### Efecto de las reseñas:
- Las puntuaciones de críticos tienen una correlación moderada positiva con las ventas (coeficiente ≈ 0.41).
- Las puntuaciones de usuarios presentan correlación casi nula, lo que sugiere que los consumidores priorizan otras métricas al elegir juegos.

#### Estretegias recomendadas
- Dado que PS4 y Xbox One se mantienen relevantes en ventas globales, recomendamos enfocar campañas publicitarias en estas plataformas.
- Debido a las preferencias de usuarios en esta región, recomendamos enfocar promociones de RPG en Japón e impulsar títulos de acción y disparos en mercados occidentales.

### Visualizaciones destacadas
1. **Distribución de ventas por género:** Gráfico de barras que muestra la popularidad relativa de los géneros en cada región.
2. **Comparación de reseñas y ventas:** Diagramas de dispersión para críticos y usuarios, destacando patrones de correlación
3. **Ventas por plataforma:** Diagramas de caja que ilustran las diferencias en ventas globales entre plataformas clave.

**Explora más detalles del proyecto en el [repositorio completo](https://github.com/MaleGoma/video-game-sales-analysis).**

## Análisis de comportamiento de usuarios y embudo de ventas

#### Herramientas y tipo de proyecto
![Python](https://img.shields.io/badge/python-357ebd?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23357ebd.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-357ebd?style=for-the-badge)
![Plotly](https://img.shields.io/badge/Plotly-%23357ebd.svg?style=for-the-badge&logo=plotly&logoColor=white)
![Limpieza de datos](https://img.shields.io/badge/Limpieza_de_datos-295F98?style=for-the-badge)
![Transformación de datos](https://img.shields.io/badge/Transformación_de_datos-295F98?style=for-the-badge)
![Análisis de datos](https://img.shields.io/badge/Análisis_de_datos-295F98?style=for-the-badge)
![Tests A/B](https://img.shields.io/badge/Tests_A/B-295F98?style=for-the-badge)
![Pruebas de hipótesis](https://img.shields.io/badge/Pruebas_de_hipótesis-295F98?style=for-the-badge)
![Visualización de datos](https://img.shields.io/badge/Visualización_de_datos-295F98?style=for-the-badge)

### Metodología

### Preguntas clave

### Conclusiones y recomendaciones

### Visualizaciones destacadas

**Explora más detalles del proyecto en el [repositorio completo](https://github.com/MaleGoma/customer-retention-analysis).**
