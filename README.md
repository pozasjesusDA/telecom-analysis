# Proyecto: Análisis de Clientes y Uso de ConnectaTel
## Objetivo del proyecto
El objetivo de este proyecto es analizar el comportamiento de los clientes de ConnectaTel mediante la limpieza, exploración y análisis de datos de usuarios, planes y uso del servicio. A partir de este análisis se busca identificar patrones de consumo, segmentar a los clientes según su edad y nivel de uso, detectar valores atípicos y generar recomendaciones que apoyen la toma de decisiones del negocio.

---

## Datasets utilizados

El proyecto utiliza los siguientes conjuntos de datos:

- **users_latam.csv:** Información demográfica de los usuarios, incluyendo edad, ciudad, plan contratado y fecha de registro, contando con un total de 4000 entradas.
- **plans.csv:** Información de los planes telefónicos disponibles, contando con un total de 2 entradas.
- **usage.csv:** Historial de uso de cada usuario, incluyendo llamadas, mensajes y duración de las llamadas; contando con un total de 40000 entradas.

---

## Etapas del análisis

Durante el desarrollo del proyecto se realizaron las siguientes etapas:

1. Carga y exploración inicial de los datos.
2. Identificación y tratamiento de valores faltantes y datos inválidos.
3. Conversión y validación de tipos de datos.
4. Integración de la información mediante la combinación de datasets.
5. Cálculo de métricas de uso por usuario.
6. Análisis estadístico de variables numéricas y categóricas.
7. Visualización de distribuciones e identificación de valores atípicos.
8. Segmentación de clientes por edad y nivel de uso.
9. Elaboración de conclusiones e insights ejecutivos.

---

## Cómo ejecutar el notebook
1. Descarga el archivo del notebook (`.ipynb`) y los datasets del proyecto.
2. Abre el notebook en **Google Colab** o **Jupyter Notebook**.
3. Coloca los archivos CSV en la carpeta indicada o modifica la ruta de lectura de los archivos si es necesario.
4. Ejecuta las celdas en orden, desde la primera hasta la última.

---
## Guía de reproducción

Para reproducir el análisis:

- Asegúrate de contar con Python  y las bibliotecas utilizadas en el proyecto (`pandas`, `matplotlib` y `seaborn`).
- Ejecuta el notebook siguiendo el orden de las celdas.
- Verifica que los archivos `users_latam.csv`, `plans.csv` y `usage.csv` se encuentren en la ruta correcta antes de iniciar la ejecución.
- Al finalizar, se generarán las tablas, gráficos y conclusiones correspondientes al análisis.
