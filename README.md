## Trabajo Práctico 2
### Elaborado por: Luis Carlos Gómez y Marget Aracelly Martínez.

Como paso previo, se realizó una carga de paquetes como *pandas*, *seaborn* y *plotly* para poder trabajar con datos desde archivos csv en forma de DataFrames y poder visualizarlos de distintas maneras. Para efectos de esta tarea estas incluyen tablas y gráficos. Luego de esto se cargaron los datos necesarios que estaban en los archivos CSV **GENERAL** y **POSITIVOS**, para así verificar el tipo de contenido que tenían, con la función *".info()"*. 

Una vez visualizado el contenido de los datos se procedió a arreglar detalles como la fecha (para poder leerla) y la eliminación de columnas y filas que no eran necesarias (valores nulos). Así como renombrar las columnas para poder leerlas de mejor manera. Una vez hecho esto se procedió a generar tablas y gráficos con plotly, mediante funciones como *go.Figure o go.Table*, *px.bar*, *plot.line* y *px.sunburst*. 

- Los datos fueron tomados de: <https://oges.ministeriodesalud.go.cr/>

[Enlace del nbviewer](https://nbviewer.org/github/margetmartinez/Datos_covid19/blob/main/Practica2.ipynb)
