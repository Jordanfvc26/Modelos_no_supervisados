![visualizaciones](ruta/de/la/imagen.png)
# Segmentación de clientes de un centro comercial

## Descripción del problema
Se busca identificar perfiles de clientes basados en ingresos, gasto y edad para personalizar campañas de marketing.

## Dataset
Mall_Customers.csv (200 registros, 5 columnas). Fuente: proporcionado por docente.

## Metodología
1. Análisis exploratorio
2. Preprocesamiento (escalado, codificación)
3. Clustering con K-means (método del codo y silueta) y DBSCAN
4. Reducción con PCA y t-SNE para visualización
5. Comparación y extracción de perfiles

## Resultados principales
- K-means identificó 5 clusters interpretables.
- DBSCAN identificó 4 clusters más ruido.
- Los perfiles incluyen: clientes de alto ingreso/alto gasto, bajo ingreso/bajo gasto, jóvenes con gasto moderado, etc.

## Cómo ejecutar
1. Instalar dependencias: `pip install -r requirements.txt`
2. Abrir `notebooks/Segmentacion_Clientes.ipynb` y ejecutar celdas.

## Integrantes
[Nombres de los miembros del equipo]
