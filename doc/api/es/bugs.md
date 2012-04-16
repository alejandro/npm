npm-bugs(3) -- Muestra en el navegador los bugs acerca de un paquete
====================================================================

## SINOPSIS

    npm.commands.bugs(paquete, callback)

## DESCRIPCIÓN

Este comando trata de encontrar, en el directorio actual, la URL donde 
se encuentra el `bug tracker` del paquete, una vez encontrado, trata de
abrirlo usando el parametro `--browser` de la configuración.

Como otros comandos, el primer parametro es un array. Este comando solo
usa el primer elemento, él cual se espera que sea un nombre de paquete
con un número de versión opcional.

Este comando lanzara un navegador, así que este comando puede que no sea 
él más agradable para uso programático.
