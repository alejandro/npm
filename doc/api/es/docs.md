npm-docs(3) -- Muestra los documentos de un paquete en el navegador
==================================================================

## SINOPSIS

    npm.commands.docs(package, callback)

## DESCRIPCIÓN

Este comando trata de adivinar, en la ubicación actual,  la URL de la
documentación de un paquete, luego trata de abrir la dirección usando 
el párametro de configuración `--browser`.

Como otros comandos, el primer parametro es un array. Este comando solo
usa el primer elemento, él cual se espera que sea un nombre de paquete
con un número de versión opcional.

Este comando lanzara un navegador, así que este comando puede que no sea 
él más agradable para uso programáti
