# Chat

## Methods

<!-- @vuese:Chat:methods:start -->
|Method|Description|Parameters|
|---|---|---|
|consultarUsuarios|Para poder esperar a que termine la operacion lo declaramos como asincrono Se consultan los usuarios disponibles con los que se puede chatear|-|
|seleccionarUsuario|Método que abre un chat cuando el usuario actual pulsa sobre otro usuario con el que desea mantener una conversación|se le pasa como argumento el usuario seleccionado con el que se quiere chatear|
|sendMessage|Se genera cuando el usuario envia un mensaje a otro|-|
|clearMessage|Se limpia el espacio de escritura de mensaje|-|
|idConversacion|Se genera un id para una conversación entre un usuario A y otro usuario B|se pasa el id del usuario emisor del mensaje y el id del receptor|

<!-- @vuese:Chat:methods:end -->


## Data

<!-- @vuese:Chat:data:start -->
|Name|Type|Description|Default|
|---|---|---|---|
|usuarios|`Array`|Array de usuarios|-|
|usuarioSeleccionado|`Null`|Usuario que tenemos seleccionado para hablar|-|
|mensaje|`String`|Variable para un mensaje|-|
|mensajes|`Array`|Array para los mensajes del chat|-|
|identificadorChat|`String`|id del Chat que importaremos de firebase|-|
|usuarioActual|`Member`|Usuario actual|-|
|receptor|`String`|Receptor|-|

<!-- @vuese:Chat:data:end -->


