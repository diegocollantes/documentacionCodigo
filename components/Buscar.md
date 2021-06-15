# Buscar

## Methods

<!-- @vuese:Buscar:methods:start -->
|Method|Description|Parameters|
|---|---|---|
|buscar|Este metodo sirve para buscar los productos del buscador|-|
|restablecerCampos|Se reestablecen los campos|-|
|aplicar|Este metodo se produce cuando se aplican los filtros para una búsqueda mas óptima|-|
|mostrarImagen|Se muestra la imagen del producto|se le pasa el id del producto a mostrar|
|añadirCesta|Se añade a la cesta el producto indicado|se pasa como argumento el id del producto a añadir|
|activarGPS|Se activa el gps para añadir coordenadas de búsqueda|-|
|haversine|Este método realiza una cuenta en la que se obtiene como resultado la distancia entre dos pares de coordenadas|pasamos como parametros la latitud y longitud del punto A y la longitud y latitud del punto b|
|recorrerProductos|Se recorren los productos que hay en el sistema|-|
|querySelections|Aqui se obtienen los valores introducidos en la búsqueda|se pasa el parametro v como valor del producto|

<!-- @vuese:Buscar:methods:end -->


## Data

<!-- @vuese:Buscar:data:start -->
|Name|Type|Description|Default|
|---|---|---|---|
|productos|`Array`|Array de productos que vamos a obtener y posteriormente mostrar|-|
|categoria|`String`|Categoria del producto|-|
|verimagen|`Null`|Imagen del producto|-|
|usuarioActual|`Member`|uid del usuario actual|-|
|idActual|`String`|id del usuario actual|-|
|coordenadas|`Object`|coordenadas actuales|-|
|coordenadas2|`Object`|coordenadas del producto|-|
|distancia|`Number`|Distancia a la que se encuentra el producto|0|
|distanciaEscogida|`String`|Distancia que ha sido escogida por el usuario|Indiferente|
|dialog|`Boolean`|Para abrir una ventana modal|false|
|loading|`Boolean`|Carga la búsqueda manual|false|

<!-- @vuese:Buscar:data:end -->


## Watch

<!-- @vuese:Buscar:watch:start -->
|Name|Description|Parameters|
|---|---|---|
|search|Va a esperar a que se carguen los elementos de la lista|se le pasa el parametro val|
|dialog|Va a añadir un tiempo de espera para que se muestre el dialog|se le pasa el parametro val|

<!-- @vuese:Buscar:watch:end -->


