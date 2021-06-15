# MisProductos

## Methods

<!-- @vuese:MisProductos:methods:start -->
|Method|Description|Parameters|
|---|---|---|
|cargarFoto|Se carga la foto del producto que el usuario pone en venta|-|
|añadirProducto|Se añade el producto a la lista de productos del usuario|-|
|recorrerProductos|Se recorren los productos para ver la lista de productos que tiene el usuario|-|
|cambiarValoresDialogs|Se cambian los valores de los dialogs para cerrar o abrir ventanas modales|-|
|limpiarValores|Se limpian los valores del formulario a rellenar para subir un producto|-|
|eliminarProducto|Se elimina el producto que haya sido seleccionado por parte del vendedor|se pasa el id del producto|
|activarGPS|Se activa el gps para añadir la geolocalización al producto que se va a poner en venta|-|
|validate|Se valida si el formulario esta bien rellenado o no|-|

<!-- @vuese:MisProductos:methods:end -->


## Data

<!-- @vuese:MisProductos:data:start -->
|Name|Type|Description|Default|
|---|---|---|---|
|dialog|`Boolean`|Para abrir la ventana modal de subir producto|false|
|dialogD|`Boolean`|Para abrir la ventana modal del producto seleccionado|false|
|min|`Number`|Mínimo de cantidad del producto que se pueda seleccionar|1|
|max|`Number`|Máximo de cantidad del producto que se puede seleccionar|100|
|productoNuevo|`Object`|Caracteristicas que va a tener el producto que vamos a poner en venta|-|

<!-- @vuese:MisProductos:data:end -->


## Watch

<!-- @vuese:MisProductos:watch:start -->
|Name|Description|Parameters|
|---|---|---|
|correcto|Tiempo de duración que va a estar la notificación|val, este sirve para activar el timeout si es true|

<!-- @vuese:MisProductos:watch:end -->


