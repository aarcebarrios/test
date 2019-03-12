# test
Ejercicio 1 - Development style guide para Ansible

Como deben nombrarse las variables:
Definimos variables globales la primera letra en mayusculas y luego minusculas.
Definimos para variables locales toda la palabra en minúsculas
Como deben escribirse los playbooks:
Definimos toda la palabra en minúsculas y una barra baja para separar.
Como deben tratarse las multilíneas:
Empezamos con una almuadilla antes de escribir las palabras, una linea contendrá como máximo 15 palabras 




Ejercicio 2 - Commit guide // workflow

Empezamos con dos ramas: Master y dev 
Cuándo tenemos un paquete a modificar, se crea una nueva rama partiendo de master que se llmará el nombre del paquete con una barra baja y eñ numero de la task.
Se realizaráhn las modificaiones necesarias y una vez testeado o vemos que funciona se mergeará a dev, junto a los otros productos que van a salir. En dev se comprobará las compatibilidades con los otros paquetes y si el resultado es sastifactorio se mergeará a master.


Ejercicio 3 - Flujo de pruebas mínimo

Que haga one-shot. 
Que funcione y haga lo deseado.
Que no genere cambios pendientes.
Que el código sea refactorizado y lejible.

