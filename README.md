
# DESAFÍO DE ANALISIS VENTAS TIENDAS ALURA STORE

El objetivo de este desafío es ayudar al señor Juan a decidir qué tienda debe vender para invertir en un nuevo negocio. Para ello, se evaluará cuál de estas cuatro tiendas tiene un desempeño menor, permitiendo al señor Juan tomar la decisión de cuál de estas cuatro tiendas debe vender para invertir en un nuevo negocio.

## Objetivo del proyecto
Idntificar la tienda con menor rendimiento en base a los datos de ventas y comportamiento de sus tiendas.

## Extracción de datos
Los datos de cada tienda están disponibles en archivos CSV y se cargaron utilizando el código base ya proporcionado.

**Estructura de datos:**
El conjunto de datos incluye la siguiente información:

Producto y Categoría: Artículos vendidos y sus calificaciones.
Precio y Envío: Valores de venta y costos asociados.
Fecha y ubicación de compra: Información temporal y geográfica.
Evaluación de compra: Comentarios de clientes.
Tipo de Pago y Cuotas: Métodos utilizados por los clientes.
Coordenadas Geográficas: Ubicación de las transacciones.

## Análisis de datos
**Ingreso total por cada tienda:**
En este primer análisis, se calcula el ingreso total de cada tienda. Sumando los valores de la columna Precio de cada conjunto de datos de la tienda para estimar los ingresos.

**Ventas por categoría**
En este punto se calcula la cantidad de productos vendidos por categoría en cada tienda. La idea es agrupar los datos por categoría y contar el número de ventas de cada tipo, mostrando las categorías más populares de cada tienda.

**Valoración media por tienda**
En este paso, se calculan las calificaciones promedio de los clientes para cada tienda. El objetivo es conocer la satisfacción del cliente con los productos vendidos.

**Productos más vendidos y menos vendidos**
En este paso, se identifican qué productos fueron los más vendidos y los menos vendidos en cada tienda se trata de visualizar los resultados para que quede claro qué productos destacaron en ventas en cada tienda.

**Valor del envío promedio por tienda**
En este paso, se alcula el costo de envío promedio para cada tienda. El objetivo es comprender cuánto se gasta, en promedio, en el envío de cada tienda.

## Generando gráficos
Después de realizar los análisis, se transforman los resultados en visualizaciones que ayuden a comprender mejor los patrones y los insights encontrados.

Los gráficos complementan el análisis realizado, resaltando los puntos más relevantes, como los ingresos de la tienda, la distribución de categorías de productos, las opiniones de los clientes, los productos más vendidos y los costes de envío.

Se emple la biblioteca Matplotlib que ofrece una variedad de tipos de gráficos que son fáciles de implementar.

## Informe Final
Con base en los análisis realizados y los gráficos generados, se sintetizan los hallazgos en un informe final explicando qué tienda debe vender el Sr. Juan, teniendo en cuenta todos los factores analizados, como:

- Los ingresos totales de las tiendas.

- Las categorías de productos más y menos vendidas.

- Las calificaciones promedio de los clientes por tienda.

- Los productos más y menos vendidos.

- El coste de envío promedio para cada tienda.

Se incluye la justificación de la decisión, respaldada por el análisis y las visualizaciones generadas y las razones por las que una tienda destaca (o no) en relación a las demás, considerando las fortalezas y debilidades de cada una.

## Tecnologías Utilizadas
* Python 3
* Google Colab
* Pandas
* Numpy
* Matplotlib
