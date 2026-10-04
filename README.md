# Grupo2_UPC_ML
Integrantes
- Willian Orestes Orozco Ramírez; 
- Nilton Yens Huanacuni Quispe; 
- Isabel Thalia Mateo Suarez

En el presente proyecto se pretende estimar la probabilidad semanal de eventos sísmicos por medio de redes neuronales artificiales a partir de data histórica e instrumental del Instituto Geofísico del Peró.
El objetivo general es: Determinar la eficacia de un modelo de red neuronal artificial para el pronóstico probabilistico semanal de eventos sísmicos de magnitud igual o superior a 4.0 para el año 2026 en Perú.
Metodología:
- Recolección de datos mediante consulta y extracción de registros del catálogo sísmico histórico del Perú, disponible en la fuente oficial del Instituto Geofísico del Perú (IGP): Fecha, Latitud, Longitud, Profundidad, Magnitud Mw.
- Consolidación en un entorno de procesamiento computacional, verificando la integridad básica de los campos y la consistencia mínima de los registros.
- Tratamiento y análisis de datos a través de una fase de limpieza, depuración, discretización espacial y construcción de secuencias temporales.
- Definición del objetivo de estimación (horizonte futuro de 7 días)
- Implementación de un modelo de redes neuronales artificiales con arquitectura recurrente bidireccional, adecuado para el análisis de dependencias temporales complejas en secuencias sísmicas.
- Partición cronológica y ajuste del modelo, con el fin de preservar la secuencia temporal y evitar fuga de información:
El conjunto de entrenamiento comprenderá los registros hasta el 31 de diciembre 2018,
El conjunto de validación abarcará la información hasta el 31 de diciembre 2021,
El conjunto de prueba incluirá los registros hasta el 31 de diciembre 2023.
-	Reentrenamiento de la versión final del modelo:
Definida la configuración final, se realizará un reentrenamiento con datos actualizados al 01 octubre 2026 (fecha corte de data sísmica IGP).
-	Estimación probabilística semanal de eventos sísmicos:
Generar ranking de las 25 zonas con mayor probabilidad relativa de actividad sísmica.
- Evaluación del desempeño (eficacia) para semanas consecutivas fuera de la muestra, es decir para el periodo del 02 de octubre 2026 hasta el 31 de diciembre del 2026, correspondientes a un total de 08 semanas.
