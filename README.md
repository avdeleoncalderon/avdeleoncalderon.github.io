# Acerca de mí

Ingeniero mecánico certificado en análisis de datos con sólida experiencia en extracción, limpieza y modelado de datos estratégicos. 

Genero insights accionables que optimizan procesos y apoyan la toma de decisiones estratégicas, logrando ahorros significativos de tiempo mediante la automatización.

### Habilidades tecnológicas
- Análisis y gestión de datos utilizando **Excel / SQL / Python / R**
- Visualización de datos y narración de historias usando **Tableau**

### Habilidades blandas
Análisis de datos | Resolución de problemas | Comunicación efectiva | Trabajo en equipo | Orientación a resultados | Organización | Proactividad | Atención al detalle | Optimización de Procesos

[![LinkedIn](https://img.shields.io/badge/LinkedIn-357ebd?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ari-vladimir/).
[![Gmail](https://img.shields.io/badge/Gmail-357ebd?style=for-the-badge&logo=gmail&logoColor=white)]av.deleoncalderon@gmail.com
* * *

# Proyectos Seleccionados

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

### Preguntas clave
1. ¿Qué factores demográficos o de comportamiento influyen más en la cancelación?
2. ¿Qué características diferencian a los clientes leales de los que abandonan?
3. ¿Cómo se pueden segmentar los clientes para diseñar estrategias personalizadas?

### Metodología
- **Preprocesamiento de datos:** Se limpiaron y estandarizaron los datos, eliminando inconsistencias y verificando la ausencia de duplicados y valores faltantes.
- **Explorartory Data Analysis (EDA):** Se analizaron características demográficas y de uso, identificando patrones en clientes que permanecen y los que cancelan.
- **Modelado predictivo:** Se entrenaron modelos de regresión logística y bosque aleatorio para predecir la cancelación de clientes con un precisión del 85% y 84%, respectivamente.
- **Clustering:** Se segmentaron los clientes en grupos utilizando K-means para identificar comportamientos similares.

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
![Contract Period Histogram](/img/p01_contract_period_histogram.png)
2. **Matriz de correlaciones:** Se encontró que Las características `month_to_end_contract` y `contract_period` están altamente correlacionadas (0.9), lo que sugiere que se debe tener cuidado con la multicolinealidad al desarrollar modelos predictivos.
![Corr Matrix Churn Data](/img/p01_gym_churn_corr.png)
3. **Análisis de clústeres:** El dendrograma muestran cómo los clientes se agrupan en segmentos distintos basados en sus características, donde el número óptimo de clústeres sugerido es 4.
![Dendrogram](/img/p01_dendrogram.png)

**Explora más detalles del proyecto en el [repositorio completo](https://github.com/avdeleoncalderon/customer-retention-analysis).**
## Análisis de comportamiento de usuarios y embudo de ventas
Este proyecto analiza el embudo de ventas de la aplicación de una empresa de alimentos para **identificar las etapas con mayores pérdidas de usuarios** y evalúa, mediante un experimento A/A/B, si un nuevo diseño de fuentes puede **mejorar la conversión** en comparación con el diseño actual. El objetivo es proporcionar **insights basados en datos** que guíen **decisiones estratégicas sobre diseño y funcionalidad**.

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

### Preguntas clave
1. ¿Qué eventos del embudo de ventas tienen mayores tasas de abandono?
2. ¿Qué porcentaje de usuarios completa el embudo de ventas desde el inicio hasta el pago?
3. ¿El cambio en el diseño de las fuentes afecta significativamente la conversión?
4. ¿Hay diferencias estadísticas entre los grupos de control y el grupo de prueba?

### Metodología
- **Preprocesamiento de datos:** Se ajustaron los nombres de las columnas, se eliminaron duplicados y se filtraron registros incompletos.
- **Análisis del embudo de ventas:** Se identificaron eventos clave y la proporción de usuarios que avanzan entre etapas.
- **Experimentación A/A/B:** Se compararon conversiones entre grupos de control y prueba mediante pruebas de hipótesis estadísticas.

### Conclusiones y recomendaciones

#### Embudo de ventas:
- El evento OffersScreenAppear es donde más usuarios abandonan (61.9%).
- Solo el 47.7% de los usuarios completa el embudo de ventas hasta el pago exitoso.

#### Resultados del experimento:
- No se encontraron diferencias estadísticas significativas entre los grupos de control y el grupo de prueba.
- Las nuevas fuentes no generan un impacto positivo en la conversión, por lo que no se recomienda implementar este cambio.

#### Recomendaciones:
- Optimizar la pantalla de ofertas para retener más usuarios en esa etapa.
- Priorizar otros cambios en el diseño o funcionalidad de la aplicación con mayor potencial de impacto.

### Visualizaciones destacadas
1. **Embudo de ventas:** La etapa en la que más se pierden usuarios es en el Tutorial, donde solo el 23.7% de los usuarios en la etapa anterior llegan a esta. La siguiente etapa donde se pierden más usuarios es en OfferScreenAppear, donde el 61.9% de los usuarios de la etapa anterior pasan a esta.
![Sales Funner Chart](/img/p03_sales_funnel_chart.png)
2. **Periodo de tiempo de los datos:** Los datos completos están disponibles a partir del 1 de agosto de 2019, por lo que se descartaron fechas anteriores. El periodo actualizado abarca del 1 al 7 de agosto de 2019.
![Time Period Data](/img/p03_time_period_data.png)

**Explora más detalles del proyecto en el [repositorio completo](https://github.com/avdeleoncalderon/sales-funnel-analysis).**

## Análisis de Base de Datos para Startup de Libros

En el contexto post-pandemia, el mercado de aplicaciones de lectura creció exponencialmente. Este proyecto analiza una base de datos de un servicio de libros para identificar **patrones de consumo, popularidad de autores y editoriales, y comportamiento de los usuarios** mediante reseñas y calificaciones. El objetivo es generar **insights accionables** que sirvan de base para la **propuesta de valor de un nuevo producto digital** dirigido a lectores.

### Herramientas y tipo de proyecto
![Python](https://img.shields.io/badge/python-357ebd?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23357ebd.svg?style=for-the-badge&logo=pandas&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-357ebd?style=for-the-badge&logo=postgresql&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-357ebd?style=for-the-badge&logo=python&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-357ebd?style=for-the-badge&logo=python&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-357ebd?style=for-the-badge&logo=tableau&logoColor=white)
![Análisis de datos](https://img.shields.io/badge/Análisis_de_datos-295F98?style=for-the-badge)
![Visualización de datos](https://img.shields.io/badge/Visualización_de_datos-295F98?style=for-the-badge)
![Base de datos relacional](https://img.shields.io/badge/Base_de_datos_relacional-295F98?style=for-the-badge)

### Preguntas clave
1. ¿Cuántos libros publicados después del año 2000 hay en el catálogo?
2. ¿Qué libros generan mayor interacción (reseñas) y mejor calificación promedio?
3. ¿Qué editorial lidera en volumen de publicaciones sustanciales (>50 páginas)?
4. ¿Qué autor tiene la calificación promedio más alta, considerando solo libros con al menos 50 calificaciones?
5. ¿Cuál es el comportamiento de los usuarios más activos (con más de 50 calificaciones) en cuanto a reseñas de texto?

### Metodología
- **Extracción de datos:** Conexión a base de datos PostgreSQL mediante `SQLAlchemy` y exploración de tablas (`books`, `authors`, `publishers`, `ratings`, `reviews`).
- **Consultas SQL:** Formulación de consultas con agregaciones, joins, subconsultas y filtros (ej. `LEFT JOIN` para preservar catálogo, `COALESCE` para valores nulos, y condiciones como `HAVING COUNT(rating_id) >= 50` para robustez estadística).
- **Análisis y visualización:** Los resultados se presentaron en DataFrames de Pandas y se generó una gráfica de barras horizontales con etiquetas integradas para comunicar el top de libros por reseñas y calificación.
- **Interpretación de resultados:** Cada hallazgo se vinculó a una conclusión de negocio, orientando futuras decisiones estratégicas.

### Conclusiones y recomendaciones
- **Catálogo moderno:** 819 libros publicados después del 2000, lo que indica una oferta actualizada y atractiva.
- **Engagement:** Sagas como *Harry Potter* y *Twilight* lideran en número de reseñas, pero *Harry Potter* mantiene una calificación superior (4.41 vs 3.66), sugiriendo que la calidad sostenida genera mayor lealtad.
- **Editorial clave:** *Penguin Books* es la editorial con más títulos de más de 50 páginas (42 libros), posicionándose como el socio comercial ideal.
- **Autor destacado:** *J.K. Rowling* presenta la calificación promedio más alta (4.29) entre libros con al menos 50 calificaciones, confirmando el valor de autores consagrados.
- **Usuarios influyentes:** Los lectores que califican más de 50 libros escriben en promedio 24.3 reseñas de texto, identificando un segmento de "super-usuarios" que generan contenido valioso para la comunidad.

**Recomendaciones estratégicas:**
- **Curaduría basada en sagas:** Implementar un sistema de recomendaciones que destaque colecciones completas.
- **Programa de "Lectores Expertos":** Crear un sistema de recompensas (badges, niveles) para usuarios con alta actividad, fomentando la generación de reseñas.
- **Alianza editorial prioritaria:** Establecer acuerdos de contenido con *Penguin Books* para garantizar un catálogo amplio.
- **Enfoque en libros modernos:** Mantener la curaduría centrada en publicaciones posteriores al año 2000.

### Visualizaciones destacadas
1. **Top 10 libros por reseñas y calificación:** Gráfico de barras horizontal que muestra el número de reseñas junto con el rating promedio integrado dentro de cada barra, facilitando la lectura rápida de los libros más conversados y mejor valorados.

![Top 10 Books](/img/p02_top_books.png)

**Explora más detalles del proyecto en el [repositorio completo](https://github.com/avdeleoncalderon/editorial-sql-analysis).**
