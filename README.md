# Proyecto de Segmentación de Clientes

## Descripción
Este proyecto utiliza técnicas de aprendizaje no supervisado para segmentar clientes basándose en sus interacciones con campañas de email marketing. El objetivo es identificar patrones de comportamiento (envíos, aperturas, clics y compras) para optimizar estrategias de marketing. Se aplicó clustering con K-Means, analizando un dataset al cual se lo limpio de inconsistencias, y se exploraron tendencias por días de la semana y horarios.

## Tecnologías utilizadas
- **Python**: Lenguaje principal para el análisis y modelado.
- **Pandas**: Manejo y limpieza del dataset.
- **NumPy**: Operaciones numéricas.
- **Scikit-learn**: Implementación de K-Means y preprocesamiento (StandardScaler).
- **Seaborn y Matplotlib**: Visualización de datos y clusters.
- **Git y GitHub**: Control de versiones y alojamiento del proyecto.

## Dataset
El dataset incluye interacciones de emails (`send`, `open`, `click`, `bounce`) y compras (`Comprador`), junto con variables temporales (`day_of_week`, `hour`).

## Resultados
Se identificaron 7 clusters de clientes, desde pasivos compradores hasta activos con alta interacción, permitiendo personalizar estrategias de envío.
