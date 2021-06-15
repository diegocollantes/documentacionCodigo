# Perfil

## Methods

<!-- @vuese:Perfil:methods:start -->
|Method|Description|Parameters|
|---|---|---|
|cargarAnteriores|Se cargan los valores anteriores del usuario|-|
|editar|Los parametros son, id -> identificador del usuario, nNuevo -> la variable que va a sustituir ,y num indica el campo Editar lo que va a hacer es cambiar el campo indicado|-|
|enviarCorreo|endof editar Se envia correo si el usuario desea cambiar de contraseña|-|
|leerDatos|Se cierran las ventanas modales que esten abiertas|-|
|guardarFoto|Se guarda la foto que haya sido subida por el usuario|-|

<!-- @vuese:Perfil:methods:end -->


## Data

<!-- @vuese:Perfil:data:start -->
|Name|Type|Description|Default|
|---|---|---|---|
|usuarios|`Array`|Para elegir al usuario que esta activo ahora mismo|-|
|usuarioAuten|`Member`|Usuario que esta en activo ahora mismo|-|
|dialog|`Boolean`|Para la ventana modal de editar|false|
|dialog2|`Boolean`|Para la ventana modal de datos nuevos|false|
|dialog3|`Boolean`|Para la ventana modal de editar foto|false|
|dialog4|`Boolean`|Para cuando se haya añadido una nueva foto|false|
|dNuevo|`String`|Dirección nueva|-|
|cNuevo|`String`|Código postal nuevo|-|
|nNuevo|`String`|Nombre nuevo|-|
|idActual|`String`|id del usuario actual|-|
|fotoPerfil|`Null`|Foto de perfil elegida por el usuario|-|

<!-- @vuese:Perfil:data:end -->


## Watch

<!-- @vuese:Perfil:watch:start -->
|Name|Description|Parameters|
|---|---|---|
|dialog2|Tiempo que vamos a ver que se ha editado correctamente|val, valor que si es verdadero espera 2 segundos|
|dialog4|Tiempo que vamos a ver que se ha editado correctamente la foto de perfil|val, valor que si es verdadero espera 2 segundos|

<!-- @vuese:Perfil:watch:end -->


