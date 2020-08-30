# Charla: Automatización de Reportes con R - un ejemplo práctico

Charla que se dictó el 23 de Julio de 2020 como parte de las conferencias que organiza la Sociedad Ecuatoriana de Estadística, en la misma se explicó cómo se podría automatizar esos reportes repetitivos que día a día nos quitan tiempo útil mediante el uso de R en conjunto con algunos de sus paquetes.

En la charla se desarrolla un caso práctico donde:
- Se conecta una base de datos con R,
- Se modifican columnas para corregir los datos,
- Se genera un reporte de **Venta por País** donde se busca ver la evolución de la venta mensual de cada país, de tal forma que cada fila representa un país-año y en las columnas se tiene los meses de venta. 
- Se hace paso a paso un reporte de **Analisis por Producto** donde se crea un indicador de la venta diciembre 2011 vs diciembre 2010, diciembre 2011 vs promedio de enero a noviembre de 2011,
- Se explora la **venta de Reino Unido**, mostrando la evolución de la venta mensual en dólares y transacciones de "United Kingdom"
- Desde R se genera un excel al que se le aplica formato de celdas (tal como un reporte final)
- Se agregan desde R fórmulas al excel creado
- Se envía el reporte por mail
- Se calendariza el reporte para que se ejecute "cada lunes"


El video de la charla pueden encontrarlo en:
https://www.facebook.com/socecuest/videos/1162544554101135/

Mientras que en este repositorio de github encontrarán el R-notebook que se muestra durante la conferencia.
https://github.com/nestormontano/2020_07_23_SEE_Charla_AutomatizacionReportesConR
