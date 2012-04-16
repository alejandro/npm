npm-config(3) -- Administra los ficheros de configuración de npm
================================================================

## SINOPSIS

    npm.commands.config(args, callback)
    var val = npm.config.get(key)
    npm.config.set(key, val)

## DESCRIPCIÓN

Esta función actua de manera similar a la versión de la linea de comandos.
El primer elemento en la array dice a la configuración que hacer. Los valores 
posibles son:

* `set`

    Establece un parámetro de configuración. El segundo elemento en `args` es
    interpretado como `key` o clave y el tercer elemento es interpretado como 
    el valor de la clave.

* `get`

    Adquiere el valor de un parámetro de la configuración. El segundo elemento en
    `args` es la `key` ó clave de donde se obtendra el valor.

* `delete` (`rm` or `del`)

    Elimina un parámetro de la configuración. El segundo elemento en `args`es la 
    `key` ó clave a eliminar.

* `list` (`ls`)

    Mustra todos los datos de configuración que no son secretos. No se necesita
    parámetros.

* `edit`:

    Abre el fichero de configuración en el editor predeterminado. Este comando
    no es muy útil programáticamente, pero esta disponible.

Para acceder programáticamente a los ajustos de configuración, o para
establecerlos durante la duración de un programa, usa mejor las funciones:
`npm.config.set` y `npm.config.get`.

## VÉASE TAMBIÉN

* npm(3)
