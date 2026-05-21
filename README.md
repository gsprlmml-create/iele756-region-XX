# iele756-region-Metropolitana de Santiago

## Equipo 17
- Gaspar Lämmel
- Fernando Rodríguez

## Comunas asignadas
- Las Condes (código 13114)
- Curacaví (código 13503)

## Anomalía del Proyecto Final
**San Pedro (código 13505) presenta una tasa ENO observada de 658 
notificaciones por 10.000 habitantes, frente a una tasa predicha de 135 
por el modelo Negative Binomial de la Tarea 3. Esto equivale a una razón 
observada/predicha de 4.87 y un residuo Pearson de 7.20, el más alto de 
las 36 comunas modeladas.**

El notebook que produce la figura principal es `notebooks/final_anomaly.ipynb`.
Tiempo de ejecución aproximado: 2-3 minutos (carga tablas pre-computadas).

## Estructura del repositorio
- `notebooks/` — notebooks de Tarea 0 a 3 y proyecto final
- `figs/` — figura principal y figuras de diagnóstico
- `requirements.txt` — dependencias del proyecto

## Cómo ejecutar

```bash
pip install -r requirements.txt
jupyter notebook notebooks/final_anomaly.ipynb
```

El notebook carga automáticamente las tablas pre-computadas desde 
Google Drive. Antes de ejecutar, asegúrate de tener acceso al Drive 
del equipo con los siguientes archivos:

| Archivo | Descripción |
|---------|-------------|
| `tarea3_analytical_table_rm_final.csv` | Tabla analítica RM (output Tarea 3) |
| `tarea3_eno_predictions_residuals.csv` | Predicciones y residuos ENO del modelo |
| `tarea3_eno_residual_extremes.csv` | Residuos extremos ENO |
| `tarea3_primary_eno_irr.csv` | IRR del modelo Negative Binomial ENO |

Estos archivos son outputs de la Tarea 3 y **no se incluyen en el 
repositorio** por su tamaño. Para reproducir el pipeline completo 
desde cero, ejecuta primero `notebooks/Tarea3_G.Lammel_F.Rodriguez.ipynb`.

## Datos originales

Los datasets del curso no están incluidos en el repositorio por su tamaño:

| Dataset | Fuente |
|---------|--------|
| `personas_censo2024.parquet` | [INE Censo 2024](https://censo2024.ine.gob.cl/resultados/) |
| `viviendas_censo2024.parquet` | [INE Censo 2024](https://censo2024.ine.gob.cl/resultados/) |
| `hogares_censo2024.parquet` | [INE Censo 2024](https://censo2024.ine.gob.cl/resultados/) |
| `20241218_base_eno_final.csv` | [DEIS MINSAL](https://deis.minsal.cl/#datosabiertos) |
| `EGRESOS_2024.zip` | Distribuido por el profesor (Canvas IELE756) |
| `CIE-10.xlsx` | Distribuido por el profesor (Canvas IELE756) |
| `Comunas.zip` | [BCN](https://www.bcn.cl/siit/mapas_vectoriales) |

## Video

[PEGAR LINK DEL VIDEO AQUÍ]

## Uso de Inteligencia Artificial

Durante el desarrollo de este proyecto utilizamos **Claude (Anthropic)** para:
- Depuración de errores en código Python y pandas a lo largo de las tareas
- Redacción y mejora de celdas markdown explicativas en los notebooks
- Revisión de interpretaciones estadísticas y redacción del guion del video

Todas las decisiones metodológicas, el análisis de los resultados y la 
interpretación de los hallazgos son responsabilidad del equipo. El código 
fue revisado, ejecutado y validado por ambos integrantes.
