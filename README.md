# AlluraDataSci01
Respuestas a prueba Allura Store
Análisis de Tiendas para Inversión


1. Propósito del análisis

El objetivo de este proyecto es ayudar a Juan a decidir en qué tienda virtual le conviene invertir su dinero. Para tomar una buena decisión, analizamos los datos históricos de cuatro tiendas diferentes. Revisamos cuánto dinero ingresan, qué categorías se venden más, qué tan contentos están los clientes y cuánto cuesta enviar los productos.
2. Estructura del proyecto

El proyecto es bastante sencillo y se compone de:

    Notebook principal (.ipynb): Un archivo de Google Colab que contiene todo el código en Python. Aquí hacemos la importación de datos, los cálculos y generamos los gráficos.

    Datos (.csv): Los datos de las cuatro tiendas se leen directamente desde enlaces crudos (raw) de GitHub usando la librería Pandas, por lo que no necesitas descargar bases de datos locales.

3. Gráficos y principales hallazgos

Al final del código, generamos un panel con tres gráficos comparativos. A partir de estos datos, sacamos las siguientes conclusiones:

    Facturación: La Tienda 1 es la que genera más dinero por lejos (más de $1,150 millones), mientras que la Tienda 4 es la que menos vende.

    Satisfacción del cliente: Todas las tiendas tienen un buen promedio (alrededor de 4 estrellas). La Tienda 3 es la mejor calificada (4.05), y la Tienda 1 la peor calificada (3.98).

    Costos de envío: La Tienda 4 tiene el envío más barato ($23,459 en promedio). La Tienda 1, a pesar de vender más, tiene el envío más caro ($26,019), lo que podría espantar a futuros clientes.

Conclusión rápida: Aunque la Tienda 1 factura más, tiene el envío más caro y la nota más baja de los clientes. Las Tiendas 2 y 3 parecen ser opciones más equilibradas y seguras para invertir.
4. Instrucciones para ejecutar el código

Para probar el código tú mismo, solo sigue estos pasos:

    Abre el archivo del notebook en Google Colab o Jupyter Notebook.

    Ve a la primera celda y ejecútala. Esto importará las librerías necesarias (pandas, matplotlib, seaborn) y descargará los datos.

    Ejecuta el resto de las celdas en orden hacia abajo.

    Al final verás impresos los resúmenes de los productos más/menos vendidos y los gráficos comparativos.
