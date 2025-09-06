🛢️ Proyecto – Predicción de Reservas y Selección de Pozos Petrolíferos en OilyGiant

Objetivo del proyecto:
Desarrollar un modelo de machine learning para predecir el volumen de reservas de pozos petrolíferos en tres regiones y seleccionar los 200 pozos más prometedores. Posteriormente, identificar la región con el mayor beneficio esperado, evaluando riesgos mediante la técnica de bootstrapping.

Procedimientos:

Exploración y preparación de datos de tres regiones (volumen de reservas y características geológicas).
Entrenamiento de modelos de regresión lineal para cada región, con división de datos en entrenamiento y validación.
Evaluación de los modelos usando RMSE y análisis de volumen promedio predicho.
Cálculo de beneficios esperados considerando:
Inversión fija de $100 millones en 200 pozos.
Precio del barril: $4.5 (equivalente a $4500 por mil unidades).
Umbral mínimo de rentabilidad: 111.1 mil barriles por pozo.
Selección de los 200 pozos con mayor volumen predicho en cada región.
Análisis de riesgos mediante bootstrapping (1000 muestras) para calcular intervalo de confianza del 95% y riesgo de pérdidas.

Conclusiones:

Se identificaron diferencias significativas en la rentabilidad de las regiones, siendo una de ellas claramente más prometedora.
El riesgo de pérdidas en la región seleccionada resultó menor al 2.5%, cumpliendo con los criterios de negocio.
El proyecto integró técnicas de regresión lineal y análisis estadístico avanzado con Python, pandas, scikit-learn, matplotlib y numpy.
