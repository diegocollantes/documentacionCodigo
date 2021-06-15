# Cesta

## Methods

<!-- @vuese:Cesta:methods:start -->
|Method|Description|Parameters|
|---|---|---|
|eliminarCesta|Se elimina de la cesta el producto|se pasa como argumento el precio del producto a eliminar y el id del producto|
|leerDatosTotal|Se cogen los productos que pertenecen a la cesta elegida por el usuario|-|
|leerDatos|Se actualiza el precio total de la cesta|-|
|pagar|Este metodo actua cuando el usuario desea pagar la cesta de productos elegidos|-|

<!-- @vuese:Cesta:methods:end -->


## Computed

<!-- @vuese:Cesta:computed:start -->
|Computed|Type|Description|From Store|
|---|---|---|---|
|calculoPrecio|-|Se calcula el precio dependiendo donde este slider|No|

<!-- @vuese:Cesta:computed:end -->


## Data

<!-- @vuese:Cesta:data:start -->
|Name|Type|Description|Default|
|---|---|---|---|
|productosCesta|`Array`|Productos que pertenecen a la cesta|-|
|idActual|`String`|id del usuario actual|-|
|dialog|`Boolean`|Para abrir la ventana modal del pago|false|
|value|`Number`|Para calcular el valor total dependiendo de los créditos usados|0|
|valueA|`Number`|Para calcular el valor total dependiendo de los créditos usados|0|
|diferencia|`Number`|Diferencia entre el valor del slider actual y anterior|0|
|precioTotal|`Number`|Precio total a pagar|0|
|creditos|`Number`|Créditos que se van a utilizar en la compra|0|
|diaA|`Number`|Día en el que se efectúa la compra|0|
|mesA|`Number`|Mes en el que se efectua la compra|0|
|anioA|`Number`|Año en el que se efectua la compra|0|
|maximo|`Number`|Tope del slider|0|
|tipoPago|`String`|Tipo de pago que se va a generar dependiendo del dinero y créditos utilizados|Efectivo|

<!-- @vuese:Cesta:data:end -->


