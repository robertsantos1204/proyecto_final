apache-airflow[snowflake]
dbt-core
dbt-snowflake
pandas

Robert Smith Santos Grullon 
2021-0956

Descripción general:
Esta guía demuestra cómo crear canales de ingeniería de datos robustos utilizando Apache Airflow para orquestar flujos de trabajo, Snowflake para el almacenamiento y procesamiento de datos, Snowpark para transformaciones escalables basadas en Python y dbt para administrar modelos de datos.

Puntos destacados:
Orquestación de datos con Airflow :

Apache Airflow administra la programación y automatización de tareas en una canalización, incluida la ingesta, transformación y validación de datos.
Almacenamiento de datos en Snowflake :

Snowflake ofrece una plataforma unificada para datos estructurados y semiestructurados. Funciones como la inferencia de esquemas y los formatos de tabla optimizados simplifican la gestión de datos.
Desarrollo de Python con Snowpark :

Snowpark permite el desarrollo escalable de Python directamente dentro de Snowflake, utilizando su potencia computacional para tareas como:
Inferencia de esquemas a partir de archivos de datos.
Ingestión de datos a través del copy_into_table()método.
Escalamiento dinámico de almacenes virtuales para optimizar el rendimiento y el costo.
Modelado de datos con dbt :

dbt facilita las transformaciones declarativas, lo que permite a los usuarios escribir modelos modulares de SQL y Python ejecutados de forma remota en Snowflake. Los procedimientos almacenados generados por dbt garantizan una ejecución sin inconvenientes dentro de Snowflake.
Integración con Snowflake Marketplace :

Incorpore fácilmente datos de terceros (por ejemplo, conjuntos de datos meteorológicos) desde Snowflake Marketplace para enriquecer sus procesos.
Beneficios:
Gestión eficiente de oleoductos de gran escala.
Modelado y transformaciones de datos simplificados.
Escalabilidad y elasticidad con los almacenes virtuales de Snowflake.
Integración perfecta con fuentes de datos externas.
Prerrequisitos:
Una cuenta Snowflake y un entorno configurado.
Conocimientos básicos de Airflow, Python y dbt.
Herramientas y bibliotecas instaladas, como snowflake-connectorproveedores de Airflow.
Para obtener la guía completa y ejemplos de código, consulte la Guía de inicio rápido de Snowflake para Apache Airflow .

