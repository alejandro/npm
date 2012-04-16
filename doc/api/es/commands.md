npm-commands(3) -- comandos de npm
================================== 

## SINOPSIS

    npm.commands[<comando>](args, callback)

## DESCRIPCIÓN

npm viene con una serie completa de comandos, y cada uno de ellos toma
una serie de argumentos similares.

En general, todos los comandos en el objeto `command` toma un array de 
argumentos **strings** posicionales. El último de los argumentos para 
culquier función es un `callback`. Algunos comandos son especiales y 
necesitan otros argumentos opcionales.

Todos los comandos tienen su propia página man. Mira `man npm-<comando>` 
para el uso en la linea de comandos, ó `man 3 npm-<comando>` para el uso 
programático.

## VÉASE TAMBIÉN

* npm-index(1)
