npm-deprecate(3) -- Depreciar la versión de un paquete
======================================================

## SINOPSIS

    npm.commands.deprecate(args, callback)

## DESCRIPCIÓN

Este comando actualizará la entrada de un paquete en el registro de npm, 
proporcionando una advertencia de depreciación en cada atento de installación 
del paquete. 


El parámetro 'args' debe tener exactamente dos elementos:

* `package[@version]`

    La porción de `version` es opcional, y puede ser un rango, una versión especifíca
    o una etiqueta.

* `message`

    El mensaje de advertencia que sera mostrado cuando un usuario intente instalar el
    paquete.

Nota que tu debes ser el propietario del paquete para depreciar algo. Véase 
`owner` y `adduser` temas de ayuda.

## VÉASE TAMBIÉN

* npm-publish(3)
* npm-unpublish(3)
* npm-registry(1)
