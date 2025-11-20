# cpv2024-vivienda-clustering

Este proyecto aplica técnicas de reducción de dimensionalidad (PCA, t-SNE, UMAP) y clustering (KMeans,HDBSCAN) sobre datos del Censo de Población y Vivienda 2024 de El SAlvador. El objetivo es identificar patrones latentes en las características habitacionales para apoyar el análisis institucional.

## Estructura del repositorio

- `data/`: Datos crudos y procesados (no se incluyen en el repositorio por privacidad)
- `notebooks/`: Análisis exploratorio y modelado en Jupyter
- `scripts/`: Funciones reutilizables para procesamiento, PCA y clustering
- `docs/`: Documentación técnica y metodológica
- `outputs/`: Tablas y gráficos generados

## Reproducibilidad

1. Clona el repositorio:
   ```bash
   git clone https://github.com/xcrero/cpv2024-vivienda-clustering.git
   cd cpv2024-vivienda-clustering

   
Los archivos son publicos solo llenar un registro 
https://geoportal.bcr.gob.sv/pages/teg-descarga-de-base-de-datos-censal-csv
# Obtención de datos

Los archivos censales utilizados en este proyecto fueron descargados desde el [GeoPortal del Banco Central de Reserva de El Salvador](https://geoportal.bcr.gob.sv/pages/teg-descarga-de-base-de-datos-censal-csv), tras completar el formulario de registro de usuario. Se utilizaron los siguientes archivos:

- `Datos.csv`: archivo original en formato CSV
- `dataset_limpio.csv`: versión procesada para análisis

Por razones de tamaño( 1.6 GB) y privacidad, estos archivos no se incluyen en el repositorio.


