# Prediccion del precio de las acciones de NVIDIA
En este proyecto realizaré un modelado predictivo del mercado de valores, y análisis de series temporales.
# Introducción
Para este proyecto utilizaré los datos diarios del precio de las acciones de Nvidia desde el 2 de enero del 2004 hasta el 1 de enero del 2024.
# Descripción de los datos
El conjunto de datos contiene datos financieros cruciales para las acciones de Nvidia, incluidos los precios de apertura, máximos, mínimos y de cierre, así como el volumen de operaciones de cada día en el período de 20 años. 
- `Date` La fecha del registro del precio de la acción.
- `Open` El precio de la acción al comienzo del día de negociación.
- `High`  El precio más alto que la acción de Nvidia alcanzó durante el día.
- `Low` El precio más bajo que la acción de Nvidia alcanzó durante el día.
- `Close` El precio de la acción al final del día de negociación.
- `Volume`  El número total de acciones de Nvidia negociadas durante el día.
# Habilidades y herramientas técnicas
- `phyton`
- `pandas`
- `matplotlib`
- `numpy`
- `scikit-learn`
# Conclusión general
En nuestro informe de resultados realizamos una **validación cruzada** para verificar si existÍa sobreajuste y obtuvimos buenos resultados en la misma sin existencia de ella.

- Comparamos dos modelos **Linear Regressor** y **Random Forest**.
- Nuestro mejor modelo fue **Linear Regressor** con un coeficiente de determinación (R²) de 0.7558, lo que indica que explica aproximadamente el 75.58% de la variabilidad en los datos.
- Este resultado sugiere que tiene un buen rendimiento general y es capaz de capturar la mayoría de las tendencias en los datos. 
- Además los indicadores de validación sugieren que el modelo está evitando el sobreajuste.
- Este modelo es  una buena opción para esta tarea de predicción!!.
