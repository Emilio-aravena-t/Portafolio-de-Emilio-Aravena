# Portafolio de Proyectos de Análisis de Datos

## Sobre Mí
¡Hola! Soy Emilio Andrés Torres Aravena, con experiencia en análisis de datos. Me apasiona trabajar con datos y extraer insights valiosos para la toma de decisiones. En este portafolio, muestro algunos proyectos en los que he trabajado, aplicando herramientas como Python, SQLite, Power BI, y más. Estos proyectos incluyen análisis de datos, visualización de datos, limpieza y transformación de datos, y automatización de datos. Los datasets utilizados provienen de Kaggle.

## Habilidades Técnicas
- **Lenguajes de Programación**: Python, SQL.
- **Bases de Datos**: SQL, SQLite.
- **Herramientas de Visualización**: Power BI, Matplotlib.
- **Librerías Python**: sqlite3, pandas, matplotlib.pyplot.

## Proyectos

### 1. Análisis de Datos de Netflix
**Descripción**: Este proyecto se enfoca en la limpieza y el análisis de un dataset de Netflix, donde se han identificado y manejado valores nulos, se eliminaron columnas innecesarias y se realizaron transformaciones en los datos para facilitar el análisis. También se analizaron las categorías de contenido, entre otros aspectos, utilizando Python y la librería pandas para la manipulación de datos.

**Habilidades Demostradas**:
- Limpieza y manejo de datos nulos.
- Eliminación de columnas irrelevantes y transformación de tipos de datos.

**Capturas**:
1. **Vista general del dataset de Netflix antes de cualquier modificación**: Muestra el estado inicial del dataset, incluyendo columnas y algunas filas. Esto es importante para entender el punto de partida antes de las modificaciones. ![Captura](capturas_netflix/Portafolio(0).png)
2. **Conteo de valores nulos por columna**: Identificación de valores faltantes en el dataset, un paso crucial para la limpieza de datos. Esto ayuda a determinar qué columnas necesitan tratamiento especial. ![Captura](capturas_netflix/portafoilio(1).png)
3. **Eliminación de columnas innecesarias y tipos de datos de cada columna**: Visualización de la eliminación de la columna `show_id` y revisión de los tipos de datos para asegurar que están preparados para el análisis. ![Captura](capturas_netflix/portafolio(2).png)
4. **Resultado del DataFrame después de las modificaciones**: Muestra el dataset después de haber eliminado columnas irrelevantes y haber transformado los tipos de datos, mostrando un ejemplo del dataset ya limpio y listo para el análisis. ![Captura](capturas_netflix/portafolio(6).png)

---

### 2. Análisis del Costo de las Misiones Espaciales
**Descripción**: Este proyecto analiza el costo y el fracaso de las misiones espaciales a lo largo del tiempo. Se identificaron patrones y tendencias, como la tasa de fracasos y la evolución del costo promedio por misión. Además, se determinó la popularidad de los lanzamientos según el mes del año. Para este análisis se utilizaron Python, pandas y matplotlib para la visualización de datos.

**Habilidades Demostradas**:
- Análisis de tendencias de costos y fracasos en misiones espaciales.
- Visualización de datos temporales y categóricos.
- Interpretación de patrones estacionales en los lanzamientos espaciales.

**Capturas**:
1. **Tasa de fracaso de misiones espaciales a lo largo del tiempo**: Muestra la cantidad de misiones que fracasaron por año, destacando patrones y tendencias. ![Captura](capturas_espaciales/captura(12.1).png)
2. **Evolución del costo promedio de las misiones espaciales por año**: Visualiza cómo el costo promedio de las misiones espaciales ha cambiado a lo largo de los años. ![Captura](capturas_espaciales/captura(8).png)
3. **Meses más populares para los lanzamientos**: Este gráfico de barras muestra los meses con mayor número de lanzamientos espaciales, identificando los meses con más actividad. ![Captura](capturas_espaciales/caputra(7.1).png)
4. **Popularidad de los lanzamientos por mes**: Gráfico que muestra la popularidad de los lanzamientos por mes, permitiendo identificar patrones estacionales. ![Captura](capturas_espaciales/captura(11.1).png)



---

### 3. Visualización de Datos de Amazon
**Descripción**: En este proyecto se analizan los datos de productos de Amazon, enfocándose en las categorías con los precios más altos, la correlación entre precio y calificación, y el rango de precios por subcategoría. El objetivo es presentar la información de manera clara a través de gráficos y análisis detallado, utilizando Python, pandas, seaborn, y Power BI para la visualización y análisis de datos.

**Habilidades Demostradas**:
- Análisis exploratorio de datos.
- Visualización de datos para identificar patrones.

**Capturas**:
1. **Código de limpieza de datos y preparación para el análisis**: Limpieza y preparación de datos de Amazon para el análisis. ![Captura](capturas_amazon/captura(0).png)
2. **Gráfico mostrando el precio promedio de los aires acondicionados y las categorías con los productos de precios más altos**: Visualiza las categorías con productos de precios elevados. ![Captura](capturas_amazon/captura_grafico(2).png)
3. **Gráfico de correlación entre precio y calificación de los productos**: Muestra la relación entre el precio y la calificación de los productos. ![Captura](capturas_amazon/captura_powerbi(3).png)

---

### 4. Análisis de Ventas con SQLite
**Descripción**: Este proyecto se basa en la manipulación y análisis de datos de ventas utilizando SQLite. Se ejecutaron consultas SQL para extraer información clave sobre ventas, productos y clientes. Los resultados se presentaron de forma estructurada para facilitar su comprensión. Además, se utilizó Python para la automatización y visualización de resultados.

**Habilidades Demostradas**:
- Consultas SQL avanzadas.
- Automatización con Python.

**Capturas**:
1. **Creación de tablas en la base de datos de ventas**: Definición de las tablas `productos`, `clientes`, `pedidos` y `ventas` para estructurar la base de datos. ![Captura](sqlite/captura_sqlite(0).png)
2. **Visualización de resultados clave obtenidos a partir de las consultas**: Ejecución de una consulta SQL que muestra los clientes por categoría y su total de compras, ordenados por el valor comprado. ![Captura](sqlite/captura_sqlite(3).png)
3. **Análisis detallado de ventas por categoría de producto**: Código Python para conectar con la base de datos y visualizar las ventas mensuales por categoría. ![Captura](sqlite/captura_sqlite(5).png)

---

### 5. Análisis de Recursos Humanos
**Descripción**: Este proyecto presenta el análisis de recursos humanos de una empresa, centrándose en la distribución de empleados según diferentes características como la región, el nivel educativo y el tipo de jornada laboral. Para la visualización de los datos se utilizó Power BI, permitiendo una interpretación interactiva y clara de la información.

**Habilidades Demostradas**:
- Análisis de recursos humanos utilizando gráficos interactivos.
- Visualización de datos para la toma de decisiones en gestión de personal.

**Capturas**:
1. **Gráfico general mostrando la distribución de empleados por región**: Visualización de la distribución de empleados de diferentes regiones, sin aplicar ningún filtro.  
   ![Captura](captura_PowerBI/powerbi(0).png)

2. **Visualización del desglose de empleados según el tipo de jornada**: Representa el desglose de empleados según la jornada laboral que tienen, ya sea presencial, remota o combinada. 
   ![Captura](captura_PowerBI/powerbi(1).png)

3. **Análisis de la distribución de empleados por nivel educativo**: Muestra cómo se distribuyen los empleados según su nivel de educación (pregrado, grado, posgrado), con el filtro aplicado al departamento de Recursos Humanos.
   ![Captura](captura_PowerBI/powerbi(2).png)



