# Grupo2_UPC_ML
Integrantes
- Willian Orestes Orozco Ramírez; 
- Nilton Yens Huanacuni Quispe; 
- Isabel Thalia Mateo Suarez

En el presente proyecto se pretende estimar espacialmente la aceleración máxima del suelo (PGA) mediante técnicas de aprendizaje supervisado y Deep Learning a partir de registros acelerométricos de la costa norte del Perú para la evaluación del peligro sísmico regional.
El núcleo de la investigación reside en la construcción del dataset a partir de los registros de redes acelerométricas, como la Red Sísmica Nacional del Instituto Geofísico del Perú (IGP) y la red del CISMID - UNI. 
-	Variables de la Fuente Sísmica (Entradas): Magnitud del momento (Mw),	Profundidad hipocentral (Z), Mecanismo de ruptura (focal).
-	Variables de Trayectoria (Propagación): Distancia epicentral y distancia hipocentral (Repi, Rhyp), Distancia más corta a la superficie de ruptura de la falla (Rrup o Rjb). 
-	Variables de Sitio (Efectos Locales): Vs30: Velocidad promedio de la onda de corte en los primeros 30 metros de profundidad (extraído de perfiles geofísicos o inferido mediante microzonificaciones sísmicas), Período fundamental del suelo (T₀) obtenido por razones espectrales H/V, Clasificación del tipo de suelo según la norma sismorresistente peruana E.030 (S₁, S₂, S₃)
