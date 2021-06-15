# Administrador

## Methods

<!-- @vuese:Administrador:methods:start -->
|Method|Description|Parameters|
|---|---|---|
|aceptar|Aceptamos la petición solicitada por el usuario|id del plastico|
|calcularCreditos|Se calcularán los créditos correspondientes que le corresponen al usuario|id del usuario|
|actualizarUsuario|Se actualizan los datos del usuario|-|
|aumentarCreditos|Se aumentan los créditos del usuario|id del usuario|
|actualizarCreditosUsuario|Se actualizan los créditos del usuario|-|
|limpiarValores|Se limpian los valores para una posterior aceptación o rechazo|-|
|limpiarListas|Se limpian los arrays debido a los cambios|-|
|rechazar|Se rechaza la peticion enviada por el usuario|-|
|actualizarArrays|Actualizamos las listas|-|
|añadirEspera|Se añade al array de plástico en espera|se pasa el objeto plástico|
|añadirAceptadas|Se añade al array de plástico aceptado|se pasa el objeto plástico|
|añadirRechazadas|Se añade al array de plástico rechazado|se pasa el objeto plástico|
|borrarNotificacion|Borramos la notificación|se pasa el id del plastico a borrar|
|actualizarOculto|Se actualiza el plastico|se pasa el id del plastico a actualizar|
|logout|Salimos de la autenticación actual y nos redirigimos a home|-|

<!-- @vuese:Administrador:methods:end -->


## Data

<!-- @vuese:Administrador:data:start -->
|Name|Type|Description|Default|
|---|---|---|---|
|notificaciones|`Array`|Se guardarán las notificaciones de plástico que esten en espera|-|
|aceptados|`Array`|Se guardarán las notificaciones de plástico que esten aceptadas|-|
|rechazados|`Array`|Se guardarán las notificaciones de plástico que esten rechazadas|-|
|usuarioAceptado|`String`|Se utilizará para saber quién es el usuario responsable de la petición|-|
|creditosConseguidos|`Number`|Indicara los creditos conseguidos por parte del usuario solicitante|0|

<!-- @vuese:Administrador:data:end -->


