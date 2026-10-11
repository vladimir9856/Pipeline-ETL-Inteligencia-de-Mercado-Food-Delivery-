# Pipeline-ETL-Inteligencia-de-Mercado-Food-Delivery-
- Contexto de Negocio
Usted ha sido contratado como Data Engineer y Analista BI por el CEO de una nueva startup
de Food Delivery que busca expandirse en Estados Unidos. Antes de lanzar la aplicación y
decidir en qué ciudades invertir, el directorio necesita entender cómo operan sus competidores
actuales, qué categorías dominan el mercado y cómo se comportan los precios según la región.

##1. Preparación del entorno de Databricks
###1.1. Arquitectura de trabajo


<div align="center">

| 📥 **EXTRACT** |
| :--- |
| CSV de restaurantes + 10 archivos de menús |

⬇️

| ⚙️ **TRANSFORM** |
| :--- |
| Limpieza, conversión de precios, filtros, control de memoria e INNER JOIN |

⬇️

| 💾 **LOAD** |
| :--- |
| Tabla maestra persistida en Databricks; SQLite cuando sea obligatorio |

⬇️

| 📊 **BUSINESS INTELLIGENCE** |
| :--- |
| 4 consultas SQL, DataFrames de resultados, gráficos y recomendaciones |

</div>




