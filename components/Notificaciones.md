# Notificaciones

## Methods

<!-- @vuese:Notificaciones:methods:start -->
|Method|Description|Parameters|
|---|---|---|
|borrarNotificacionAceptada|Se borra la notificación aceptada|se pasa el id de la notificación a borrar|
|actualizarValoresAceptacion|Se actualizan las peticiones aceptadas y concurridas|-|
|actualizarValoresRechazo|Se actualizan las peticiones rechazadas y concurridas|-|
|borrarNotificacionRechazada|Se borra la notificación rechazada a elegir|se pasa como argumento el id de la notificación a borrar|
|actualizarAceptadas|Se actualizan las peticiones aceptadas|-|
|actualizarRechazadas|Se actualizan las peticiones rechazadas|-|
|actualizarMensajes|Se actualizan las peticiones de mensajes no leidos|-|
|actualizarPeticion|Se actualizan las peticiones|-|

<!-- @vuese:Notificaciones:methods:end -->


## Data

<!-- @vuese:Notificaciones:data:start -->
|Name|Type|Description|Default|
|---|---|---|---|
|notificaciones|`Array`|Para los mensajes|-|
|espera|`Array`|Para las peticiones en espera|-|
|aceptadas|`Array`|Para las peticiones aceptadas|-|
|rechazadas|`Array`|Para las peticiones rechazadas|-|
|idUsuarioActual|`String`|id del usuario actual|-|
|mensajesSleer|`Number`|Número de mensajes que hay sin leer por parte del usuario|0|
|peticionesConcurridas|`Number`|Número de peticiones que han sido concurridas|0|
|peticionesAceptadas|`Number`|Número de peticiones que han sido aceptadas|0|
|peticionesRechazadas|`Number`|Número de peticiones que han sido rechazadas|0|

<!-- @vuese:Notificaciones:data:end -->


