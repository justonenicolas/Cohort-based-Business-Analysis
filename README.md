# Cohort-based-Business-Analysis
Proyecto de análisis de negocio segmentado por cohortes

## Etapas que componen el proyecto

## Preparación y Enriquecimiento de los datos
En esta etapa se realizará una primera revisión de los datos que permita comprender cómo se componen los datasets y tener una noción general de la información. Una vez cargada la información y tras realizar algunos planteamientos iniciales, se procederá a recorrer los datos en busca de posibles errores en la información que deban ser solucionados (tipo de objeto, formato, valores duplicados, valores ausentes) 

Luego de haber limpiado y organizado la información, se procederá a añadir campos que permitan o faciliten la resolución de dudas, preguntas e hipótesis con base en los datos iniciales

## Cálculo de métricas e informes
Después de haber organizado los datos para su análisis, se procederá a agrupar la información de la manera más conveniente de tal modo que permita comenzar a responder los planteamientos y que se puedan comenzar a incluir gráficas que faciliten el análisis estadístico y de negocio con la información disponible

### Métricas de Visitas
### Métricas de Ordenes
### Métricas de Marketing


## Conclusiones generales
---------------

# Descripción de los datos
- **Tabla Visits** (Registros del servidor con datos sobre las visitas al sitio web):

    - **uid**: identificador único del usuario

    - **device**: dispositivo del usuario

    - **start ts**: fecha y hora de inicio de la sesión

    - **end ts**: fecha y hora de término de la sesión

    - **source Id**: identificador de la fuente de anuncios de la que proviene el usuario


- **Tabla Orders** (datos sobre pedidos):

    - **uid**: identificador único del usuario que realiza un pedido

    - **buy ts**: fecha y hora del pedido

    - **revenue**: el ingreso de Showz por el pedido


- **Tabla Costs** (datos sobre gastos de marketing):

    - **source_id**: identificador de la fuente de anuncios
    
    - **dt**: fecha
    
    - **costs**: gastos en esta fuente de anuncios en este día
