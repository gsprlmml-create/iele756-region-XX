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

## Uso de IA
Durante el desarrollo de este proyecto utilizamos Claude (Anthropic) para:
- Depuración de código Python y pandas
- Redacción de celdas markdown explicativas en los notebooks
- Revisión de interpretaciones estadísticas

Todo el análisis, las decisiones metodológicas y la interpretación de 
resultados son responsabilidad del equipo.

## Video
[Link al video — agregar antes de la entrega]

## GitHub
https://github.com/gsprlmml-create/iele756-region-XX
