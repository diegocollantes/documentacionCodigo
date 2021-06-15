# Plastico

## Methods

<!-- @vuese:Plastico:methods:start -->
|Method|Description|Parameters|
|---|---|---|
|allowedDates|Se limitan los dias de elección del calendario|-|
|enviarPlastico|Se envía la peticion de plástico por parte del usuario|-|
|recogerDireccion|Se recoge la dirección del usuario que va a realizar la petición|-|
|mostrarDialog|Mostrar la el la ventana modal de la alerta|-|
|restablecerValores|Se reestablecen los valores|-|

<!-- @vuese:Plastico:methods:end -->


## Data

<!-- @vuese:Plastico:data:start -->
|Name|Type|Description|Default|
|---|---|---|---|
|plasticoNuevo|`Object`|Va a obtener los campos que se van a rellenar en la solicitud del plástico|-|
|modal|`Boolean`|Para la ventana modal del calendario|false|
|modal2|`Boolean`|Para la ventana modal del reloj|false|
|fechaAhora|`Call`|Fecha actual|-|
|dialog|`Boolean`|Para ver si la notificación esta abierta|false|

<!-- @vuese:Plastico:data:end -->


## Watch

<!-- @vuese:Plastico:watch:start -->
|Name|Description|Parameters|
|---|---|---|
|dialog|Se abre la notificación de que la petición de plástico ha sido realizada|-|

<!-- @vuese:Plastico:watch:end -->


