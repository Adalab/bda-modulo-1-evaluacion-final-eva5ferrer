## Evaluación Módulo 1 Data Analytics de Eva Ferrer

Este ejercicio forma parte de la evaluación del módulo 1 del bootcamp de Data Analysis & AI. 
El objetivo de esta evaluación es evaluar mis conocimientos de Python aprendidos durante el módulo 1, junto con el uso de las herramientas Visual Studio Code y los notebook Jupyter.

Concretamente, en esta evaluación he podido aplicar los conceptos de variables, listas, diccionarios y funciones, así como poder aprender la lógica que hay detrás de cada código.

El ejercicio se divide en dos partes principales:

## A. Crear las estructuars principales:
En esta parte he definido las estructuras principales que se van a usar durante el ejercicio: 
* inventario (lista de diccionarios)
* cliente (diccionario)
* ventas_totales (float)

## B. Funciones:
En esta parte he podido definir 7 funciones distintas para poder realizar diferentes acciones, siempre involucrando la lista de inventario creada anteriormente en la parte 1. 

# 1. agregar_producto (nombre, precio, cantidad)
Con esta función he podido agregar productos al inventario o actualizar su cantidad si el producto ya estaba en el inventario. 
Los parámetros de la función son: nombre, precio y cantidad.

# 2. ver_inventario()
Con esta función he podido imprimir los detalles del inventario de una forma específica y más clara.

# 3. buscar_producto(nombre)
Con esta función he podido buscar cualquier producto en el inventario y así poder mostrar sus detalles (nombre, precio y cantidad) si se encuentra.
En el caso de no encontrarse en el inventario, se lo indico al usuario.
Los parámetros de la función en este caso son: nombre.

# 4.  actualizar_stock(nombre, cantidad)
Al definir esta función, he podido actualizar el stock de un producto en el inventario. 
Los parámetros de la función son: nombre y cantidad.

# 5. eliminar_producto(nombre)
El objetivo de definir esta función es la de poder eliminar un producto del inventario en el caso que tengamos este producto disponible. 
Los parámetros de la función son: nombre.

# 6. calcular_valor_inventario()
Con esta función he podido calcular el valor total del inventario.

# 7. realizar_compra()
Esta es la función más complicada de definir. Con ella he permitido a un cliente relizar una compra seleccionando productos del inventario e ir introduciéndolos en un carrito de la compra y calcular el costo total de la compra del clinete. Por supuesto, el inventario se va actualizando a medida que el cliente va comprando. 
 
