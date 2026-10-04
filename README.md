# Proyecto final: Online Retail

**Asignatura:** SM26_CIA6041 – AI and Organizational Data Management  
**Integrante:** Felipe Gerardo Rodríguez Cordero

## Problema y pregunta de negocio

Un comercio minorista en línea necesita identificar clientes de mayor valor y clientes con menor actividad.

**¿Cómo utilizar el historial de compras para orientar acciones de fidelización y reactivación, y estimar la recompra en los próximos 90 días?**

## Contenido y estructura

Los entregables se encuentran en la carpeta principal del repositorio:

- **Notebook (.ipynb):** preparación de datos, EDA, árbol de decisión y segmentación RFM con K-Means.
- **Dashboard (.twbx):** libro de Tableau con su fuente de datos incluida.
- **PDF de capturas:** vistas principales del dashboard.
- **Informe técnico (PDF):** metodología, resultados, recomendaciones, limitaciones, reflexión ética y declaración de uso de IA.

## Cómo ejecutar el proyecto

### Notebook

1. Descargar el notebook del repositorio.
2. Abrirlo en Google Colab mediante **Archivo → Subir notebook**.
3. Seleccionar **Entorno de ejecución → Ejecutar todas**.
4. Cuando se solicite, cargar el Excel original del dataset Online Retail.
5. Revisar las salidas, los gráficos y sus interpretaciones.

Fuente del dataset: https://doi.org/10.24432/C5BW33

El Excel original se obtiene desde la fuente indicada. La ejecución genera el archivo `online_retail_depurado.csv`.

### Dashboard

Descargar el archivo `.twbx` y abrirlo en Tableau Desktop o en una edición compatible. La fuente de datos está incluida en el archivo empaquetado. El PDF de capturas permite consultar las vistas sin abrir Tableau.

## Resultados principales

- Registros originales: **541,909**.
- Registros después de limpieza: **524,878**.
- Registros con CustomerID: **392,692**.
- Clientes identificados: **4,338**.
- Exactitud de la línea base: **73.34%**.
- Exactitud del árbol: **74.60%**, una mejora de **1.26 puntos porcentuales**.
- K-Means: **2 segmentos**, con Silhouette Score de **0.4328**.
- Cluster 0: **2,672 clientes** con menor actividad.
- Cluster 1: **1,666 clientes** con compras más recientes, frecuentes y de mayor valor.

## Recomendaciones y
