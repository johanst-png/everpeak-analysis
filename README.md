# everpeak-analysis
ConnectaTel — Análisis de Clientes de Telecomunicaciones

🎯 Objetivo del proyecto

El objetivo de este proyecto es analizar el comportamiento de los clientes de ConnectaTel, una empresa de telecomunicaciones en Latinoamérica, para identificar patrones de uso, detectar comportamientos atípicos y segmentar a los usuarios según su nivel de consumo.

Este análisis permite apoyar decisiones de negocio como:

Optimización de planes móviles
Mejora de la experiencia del cliente
Estrategias de retención
Identificación de usuarios de alto valor


📁 Datasets utilizados

El análisis se basa en tres fuentes principales de datos:

plans.csv → Información de los planes (precio, minutos incluidos, GB, costos extra).
users.csv → Información de los clientes (edad, ciudad, fecha de registro, plan, churn).
usage.csv → Registro de uso de servicios (llamadas, mensajes, duración, longitud).


🧭 Etapas del análisis

El proyecto se desarrolló en las siguientes fases:

Carga y exploración de datos
Revisión de estructura, tipos de datos y valores faltantes.
Identificación de problemas de calidad
Detección de nulos, sentinels y valores inconsistentes.
Limpieza de datos
Corrección de edades inválidas, ciudades faltantes y fechas fuera de rango.
Análisis descriptivo
Estadísticas generales de uso por usuario.
Visualización de datos
Histogramas y boxplots para entender distribuciones y outliers.
Segmentación de clientes
Clasificación por nivel de uso y grupo de edad.
Insights ejecutivos
Traducción de hallazgos en recomendaciones de negocio.


▶️ Cómo ejecutar el notebook

Puedes ejecutar este proyecto en Google Colab o Jupyter Notebook.

Opción 1: Google Colab
Abre https://colab.research.google.com/
Sube el archivo .ipynb
Sube los datasets (plans.csv, users.csv, usage.csv)
Ejecuta las celdas en orden
Opción 2: Jupyter Notebook local
Instala dependencias:
pip install pandas numpy matplotlib seaborn
Abre Jupyter:
jupyter notebook
Ejecuta el archivo .ipynb


🔁 Guía de reproducción

Para reproducir el análisis correctamente:

Cargar los datasets en el orden indicado.
Ejecutar primero la limpieza de datos antes del análisis.
Mantener el orden del notebook (no saltar celdas).
Verificar que las columnas agregadas (user_profile, segmentaciones) estén correctamente creadas antes de visualizaciones.
Ejecutar las celdas de visualización después de la agregación de datos.
📌 Resultados principales
La mayoría de usuarios se concentra en niveles de uso medio.
Los usuarios adultos representan el segmento principal.
Se identificaron outliers que corresponden a usuarios de alto consumo.
Existen oportunidades de mejora en la segmentación de planes.
👨‍💻 Autor

Proyecto de análisis de datos — ConnectaTel
Hecho con Python (pandas, numpy, seaborn, matplotlib)
