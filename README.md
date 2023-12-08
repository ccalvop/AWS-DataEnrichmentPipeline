<p align="center">
<img src="https://github.com/ccalvop/AWS-DataEnrichmentPipeline/assets/126183973/aa5f6aea-a4d2-46c3-9ffe-f818086ba3f2" />
</p>

# <p align="center">AWS-DataEnrichmentPipeline</p>

![diagram](https://github.com/ccalvop/AWS-DataEnrichmentPipeline/assets/126183973/0032b83a-9d8e-4aee-a9c1-02be8c41c34e)

**Objetivo:**

Desarrollar un pipeline de enriquecimiento de datos utilizando AWS Glue, Amazon API Gateway y AWS Lambda. El objetivo es tomar datos crudos almacenados en Amazon S3, procesarlos y enriquecerlos con información adicional de fuentes externas, y finalmente proporcionar una API REST para acceder a los datos enriquecidos.

**Servicios AWS utilizados:**

  - AWS Glue: Para el procesamiento y transformación de datos.
  - Amazon S3: Para almacenar los datos crudos y enriquecidos.
  - Amazon API Gateway: Para crear la API REST.
  - AWS Lambda: Para ejecutar el código que enriquecerá los datos y responderá a las solicitudes de la API.

**Archivos y código a crear:**

  - Crear un flujo de trabajo de AWS Glue para extraer, transformar y cargar datos crudos almacenados en un bucket de Amazon S3 en un formato adecuado para el análisis.
  - Utilizar AWS Glue DataBrew para limpiar, enriquecer y preprocesar los datos, aplicando transformaciones y correcciones necesarias.
  - Configurar un punto de enlace en Amazon API Gateway para exponer los datos enriquecidos a través de una API REST.
  - Desarrollar funciones de AWS Lambda para procesar las solicitudes de la API, acceder a los datos enriquecidos y proporcionar respuestas adecuadas.
  - Integrar servicios adicionales de AWS, como Amazon DynamoDB para almacenar metadatos y Amazon CloudWatch para monitorear y generar alertas sobre la ejecución del flujo de trabajo.
  - (*)Implementar la automatización del flujo de trabajo utilizando AWS Step Functions para coordinar las diferentes etapas del proceso de enriquecimiento de datos.
  - (*)Desarrollar una interfaz de usuario o dashboard para visualizar los datos enriquecidos y permitir la interacción con los datos de manera intuitiva.

**Resumen del proceso:**

  - Configurar un bucket de Amazon S3 para almacenar los datos crudos y otro bucket para almacenar los datos enriquecidos.
  - Utilizar AWS Glue para crear un catálogo de datos y definir un job de ETL (Extraction, Transformation, Load) para procesar y enriquecer los datos.
  - Configurar un punto de enlace en Amazon API Gateway y definir los recursos y métodos necesarios para acceder a los datos enriquecidos.
  - Crear funciones de AWS Lambda que se ejecuten cuando se llame a los métodos de la API, procesen los datos y proporcionen la respuesta adecuada.
  - Probar el pipeline completo, asegurándose de que los datos crudos se procesen y enriquezcan correctamente, y que la API responda con los datos enriquecidos.

**Resultado esperado:**

Un pipeline completamente funcional que tome datos crudos, los enriquezca con información adicional y los exponga a través de una API REST para su acceso y consulta. Los datos enriquecidos estarán disponibles para su análisis y podrán utilizarse para obtener información valiosa.

Este proyecto combina la analítica de datos con la automatización de servicios de AWS, lo que lo convierte en una solución potente y escalable para enriquecer y acceder a grandes volúmenes de datos de manera eficiente. Además, proporciona una base sólida para futuras iteraciones y mejoras en el procesamiento y análisis de datos.

***
![underconstruction_ccalvop](https://github.com/ccalvop/ML-TrafficInsights/assets/126183973/b9de3820-25a3-45dc-ab38-e65d96460d83)


TIME - 2023-12-08 11:46:39