Proyecto de Almacén de Datos y Análisis
¡Bienvenido al repositorio de Data Warehouse and Analytics Project! 🚀
Este proyecto demuestra una solución integral de almacenamiento de datos y analítica, desde la construcción de un almacén de datos hasta la generación de insights accionables. Diseñado como un proyecto de portafolio, destaca las mejores prácticas del sector en ingeniería y análisis de datos.

🏗️ Arquitectura de datos
La arquitectura de datos de este proyecto sigue las capas Medallion Architecture Bronze, Silver y Gold: Arquitectura de datos

Capa de bronce: Almacena datos en bruto tal cual proceden de los sistemas fuente. Los datos se ingieren de los archivos CSV en la base de datos SQL Server.
Capa de plata: Esta capa incluye procesos de limpieza, estandarización y normalización de datos para preparar datos para su análisis.
Gold Layer: Alberga datos listos para el negocio modelados en un esquema estrella necesario para informes y análisis.
📖 Resumen del proyecto
Este proyecto implica:

Arquitectura de datos: Diseñando un almacén de datos moderno utilizando capas de bronce, plata y oro de la arquitectura Medallion.
Pipelines ETL: Extraer, transformar y cargar datos de los sistemas fuente al almacén.
Modelado de datos: Desarrollo de tablas de hechos y dimensiones optimizadas para consultas analíticas.
Analítica e Reportes: Creación de informes y paneles basados en SQL para obtener información accionable.
🎯 Este repositorio es un recurso excelente para profesionales y estudiantes que buscan mostrar experiencia en:

Desarrollo SQL
Arquitecto de Datos
Ingeniería de Datos
Desarrollador de pipeline ETL
Modelado de datos
Análisis de datos
🛠️ Enlaces y herramientas importantes:

Conjuntos de datos: Acceso al conjunto de datos del proyecto (archivos csv).
SQL Server Express: Servidor ligero para alojar tu base de datos SQL.
SQL Server Management Studio (SSMS): GUI for managing and interacting with databases.
Git Repository: Set up a GitHub account and repository to manage, version, and collaborate on your code efficiently.
DrawIO: Design data architecture, models, flows, and diagrams.
Notion: Get the Project Template from Notion
Notion Project Steps: Access to All Project Phases and Tasks.
🚀 Project Requirements
Building the Data Warehouse (Data Engineering)
Objective
Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and informed decision-making.

Specifications
Data Sources: Import data from two source systems (ERP and CRM) provided as CSV files.
Data Quality: Cleanse and resolve data quality issues prior to analysis.
Integration: Combine both sources into a single, user-friendly data model designed for analytical queries.
Scope: Focus on the latest dataset only; historization of data is not required.
Documentation: Provide clear documentation of the data model to support both business stakeholders and analytics teams.
BI: Analytics & Reporting (Data Analysis)
Objective
Develop SQL-based analytics to deliver detailed insights into:

Customer Behavior
Product Performance
Sales Trends
These insights empower stakeholders with key business metrics, enabling strategic decision-making.

For more details, refer to docs/requirements.md.

📂 Repository Structure
data-warehouse-project/
│
├── datasets/                           # Raw datasets used for the project (ERP and CRM data)
│
├── docs/                               # Project documentation and architecture details
│   ├── etl.drawio                      # Draw.io file shows all different techniquies and methods of ETL
│   ├── data_architecture.drawio        # Draw.io file shows the project's architecture
│   ├── data_catalog.md                 # Catalog of datasets, including field descriptions and metadata
│   ├── data_flow.drawio                # Draw.io file for the data flow diagram
│   ├── data_models.drawio              # Draw.io file for data models (star schema)
│   ├── naming-conventions.md           # Consistent naming guidelines for tables, columns, and files
│
├── scripts/                            # SQL scripts for ETL and transformations
│   ├── bronze/                         # Scripts for extracting and loading raw data
│   ├── silver/                         # Scripts for cleaning and transforming data
│   ├── gold/                           # Scripts for creating analytical models
│
├── tests/                              # Test scripts and quality files
│
├── README.md                           # Project overview and instructions
├── LICENSE                             # License information for the repository
├── .gitignore                          # Files and directories to be ignored by Git
└── requirements.txt                    # Dependencies and requirements for the project
