# GestionInventarioJava

Esta app interactua con una base de datos para:
- Crear
- Actualizar
- Eliminar
- Consultar

Esta APP puede:

- Añadir productos a stock en inventario
- Eliminar productos de stock
- Actualizar los datos de los productos
- Consultar inventario
- Crear informes de ganancias, ingreso/egreso de stock
- Crear Alertas 


Preguntas frecuentes:

¿Que gestor de base de datos se utiliza?
- Actualmente SQLLite por ser una opcion rapida,ligera y portable.

¿La base de datos es de gran tamaño debido a las imagenes?
- No, en esta implementacion se almacenan las url de cada imagen por lo que no deberia afectar significativamente el tamaño.

¿De donde se provienen los datos de la BD?

- Me tome el trabajo de crear un webscrapper especificamente para archivos html en este caso fui descargando listados de stock de la pagina preciosclaros.gob.ar
