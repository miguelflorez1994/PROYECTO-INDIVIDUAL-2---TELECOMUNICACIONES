<h1 align='center'>
PROYECTO INDIVIDUAL 2 TELECOMUNICACIONES
</h1>

# Introducción

![Análisis de datos](imágenes/analisis_datos.jpg)

Este proyecto tiene como propósito principal realizar un análisis integral de los datos relacionados con el acceso a Internet en la República Argentina, utilizando los conjuntos de datos publicados en el portal del Ente Nacional de Comunicaciones (ENACOM). El objetivo es desarrollar y proponer una serie de Indicadores Clave de Desempeño (KPI) que sean relevantes para una empresa consultora especializada en servicios de telecomunicaciones, interesada en establecerse en el mercado argentino. 

![ENACOM](imágenes/Logo_enacom.png)

Para lograr este objetivo, se implementará un enfoque metodológico estructurado en varias etapas. En primer lugar, se llevará a cabo un proceso de Extracción, Transformación y Carga (ETL) para depurar y estandarizar los datos disponibles, asegurando su calidad y consistencia para su posterior análisis. Posteriormente, se aplicará un Análisis Exploratorio de Datos (EDA) que permitirá identificar patrones significativos, detectar relaciones entre variables clave y gestionar valores atípicos o anómalos que puedan distorsionar los resultados.

Este enfoque permitirá no solo comprender en detalle la situación actual del acceso a Internet en el territorio argentino, sino también identificar áreas críticas de mejora en términos de cobertura, velocidad y equidad en la conectividad. Como resultado, se generarán recomendaciones técnicas y estratégicas para optimizar la penetración del servicio en hogares y comunidades, con un enfoque en maximizar la competitividad de la empresa consultora y fomentar el desarrollo de una infraestructura digital más inclusiva en el país.

# Índice

1. [Introducción](#introducción)
2. [Fuentes de datos](#fuentes-de-datos)
3. [Recursos utilizados](#recursos-utilizados)
4. [ETL: Extracción, Carga y Transformación de Data](#etl-extracción-carga-y-transformación-de-data)
5. [EDA: Análisis Exploratorio de Datos](#eda-análisis-exploratorio-de-datos)
6. [Formulación de KPI`s](#formulación-de-kpis)
7. [Conclusiones](#conclusiones)
8. [Autor](#autor)

# Fuentes de datos

A continuación se dejan las fuentes de datos utilizadas para el proyecto:

[Datasets](https://indicadores.enacom.gob.ar/datos-abiertos)    
[Diccionario de datos](https://docs.google.com/document/d/1BYW0vT_DNIjjKM9v4hNg5KmqjRNOc7OBB1jCXc80gnI/edit?pli=1&tab=t.0)

# Recursos utilizados

- [Python](https://www.python.org/)
- [Powerbi](https://www.microsoft.com/es-es/power-platform/products/power-bi)
- [Excel](https://www.microsoft.com/es-es/microsoft-365/excel)
- [Visual Code Studio](https://code.visualstudio.com/)


# ETL: Extracción, Carga y Transformación de Data

Se llevan a cabo procesos detallados de revisión y limpieza del dataset "Internet," el cual recopila información sobre la conectividad en Argentina durante los últimos 10 años. Estos procesos incluyen la identificación y tratamiento de valores nulos, la detección y eliminación de registros duplicados, así como la corrección de errores en la escritura y el manejo adecuado de símbolos o caracteres especiales que puedan afectar la calidad del análisis. Para garantizar un entendimiento claro y preciso de las variables clave presentes en el dataset, se emplea como referencia el diccionario de datos asociado. Este documento guía el análisis al proporcionar una comprensión estructurada de las variables, su significado y relevancia en el contexto del estudio, lo que permite una preparación de datos sólida y alineada con los objetivos de análisis en el ámbito de la conectividad nacional.

![Tecnologías conectividad](imágenes/TECH-INTERNET.png)

# EDA: Análisis Exploratorio de Datos

Se puede entender el comportamiento sobre la expansión de las redes de internet en Argentina si se revisan los planes que han venido sucediendo en el último tiempo:  

![Acceso cada 100 hogares](imágenes/accesosx100hogares.png)

1. **Crecimiento de la conectividad en áreas urbanas y rurales**  
   Aunque las zonas urbanas, como Buenos Aires, han liderado en términos de acceso a internet de alta velocidad, en los últimos años se han implementado políticas y programas para reducir la brecha digital en áreas rurales y menos desarrolladas. Programas como "Plan Conectar" buscan extender la infraestructura de fibra óptica para abarcar regiones más alejadas.  

2. **Participación del Estado y actores privados**  
   El gobierno argentino, a través de empresas como ARSAT, ha jugado un papel importante en la expansión de la Red Federal de Fibra Óptica (REFEFO), que conecta provincias y localidades. Paralelamente, proveedores privados como Telecom, Movistar y Claro también han expandido sus redes para satisfacer la creciente demanda.  

3. **Impacto del acceso móvil y tecnologías 4G/5G**  
   El acceso a internet móvil ha crecido significativamente, con un fuerte impacto en la adopción de tecnología 4G. En los últimos años, se ha trabajado en la incorporación de redes 5G en el país, lo que promete acelerar aún más la conectividad y permitir aplicaciones más avanzadas.  

4. **Desafíos económicos y sociales**  
   A pesar del avance, factores como la desigualdad económica y los altos costos de algunos servicios de internet siguen limitando el acceso para ciertos sectores de la población. Además, las velocidades promedio de internet en el país, aunque en mejora, aún están por debajo de los estándares globales, lo que representa un reto a superar.  

# Formulación de KPI's

Los siguientes  indicadores claves planteados ayudan a entender si las estrategias de mejora en cuanto a conectividad en el territorio nacional están siendo efectivas. Los KPI's son los siguientes:

- Nuevos Accesos Cada 100 Hogares (NACH): Este indicador clave de desempeño (KPI) representa el primer parámetro solicitado por el cliente, diseñado para evaluar el crecimiento bruto en la conectividad de la red a nivel provincial. El NACH se define como el incremento en el número de accesos a Internet por cada 100 hogares dentro de una región específica.

    Se ha establecido una meta preliminar de aumento del 2% en el valor del NACH, la cual se considera alcanzable en áreas con niveles de acceso más bajos, dado que estas presentan un mayor potencial de expansión. Sin embargo, en provincias con un alto grado de desarrollo y una penetración significativa de Internet, este objetivo resulta mucho más desafiante debido a la saturación del mercado y la complejidad de captar nuevos usuarios.

    Este KPI es particularmente valioso porque proporciona una visión clara del ritmo de expansión de la infraestructura y los servicios de conectividad. Su análisis permite identificar áreas estratégicas para la inversión, priorizando aquellas donde el impacto del crecimiento puede ser mayor, y también resalta los desafíos asociados con mantener tasas de crecimiento sostenidas en regiones ya desarrolladas. Esto lo convierte en una métrica crítica para diseñar planes de expansión alineados con las oportunidades y limitaciones de cada provincia.

![NACH](imágenes/NACH.png)

# Conclusiones

Se tienen varias conclusiones al respecto:

1. Debido a la gran extensión del territorio y la poca densidad poblacional fuera de la provincia de Buenos aires y de las grandes ciudades de los departamentos se hace indispensable la inversión en infraestructura para la conectividad por parte de programas del gobierno como lo viene haciendo actualmente, especialmente con la ReFeFo (Red Federal de Fibra Óptica) una tecnología que viene en aumento en todo el territorio nacional.

2. La expanción y masificación de la internet satelital como starlink, permitirá a las zonas rurales tener acceso a internet de alta velocidad, lo que generará un crecimiento en la conectividad y en la economía de las zonas rurales.

3. El papel desempeñado por ENACOM en la regulación y supervisión de la industria de las telecomunicaciones es fundamental para garantizar la competencia y la calidad de los servicios. Su labor es crucial para promover la inversión y el desarrollo de la infraestructura de telecomunicaciones en todo el país.

4. Gracias a la creación de actores como ARSAT, las redes de fibra óptica han tenido un crecimiento importante en todo el país, lo que ha permitido que empresas cooperativas y Pymes puedan tener una oportunidad de ofrecer servicios de conectividad a sus clientes.

# Autor

Miguel Flórez Betancourt

[¡Contáctame con un email!](miguelandres.florez@gmail.com)

Contacto profesional 
[Linkedin](www.linkedin.com/in/miguel-flórez-betancourt-251508121)
