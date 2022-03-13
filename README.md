# Aprendiendo a crear una pagina web

Este es un  resumen de un ejemplo de creacion de pagina web. 

## Programas a instalar 

1- Edior Sublime text 3 (Para editar el codigo de la pagina web)

2- Git (Se usa para manterner el codigo en remoto, ademas de la version en localcon la que trabajamos)

3- Node.js 

4- Browser-sync (Sirve para que la pagina aplique los ultimos cambios efectuados automaticamente)

## Primeros pasos

1- Crear una cuenta Git y crear un repositorio. Ir a settings -> pages, para que la pagina sea hospedada en GIt (aun tengo dudas si "Hospedar" es el termino correcto).

2- Clonar el repositorio (ejecutar: git clone XXX, donde XXX se encuentra en git -> Code -> HTTPS y es de la forma https://github.com/...).

3- Cada vez que efectuamos un cambio en el repositorio, si queremos agregarlos al projecto hay que ejecutar:

- git add . (el putno es para agregar todo, pero podemos ser mas especificos si solo queremos agregar un archivo)
- git commit -m "Mensaje para entender que cambios han sido efectuados" (la -m es de mensaje, y el mensaje que escribamos nos va a aclarar que cambios fueron aplicados)
- git push (Esto es para incluir tambien los cambios en el repositorio remoto, porque hasta el momento solo estan aplicados en la maquina local).

Podemos consultar el estado de la rama actual de git ejecutando

- git status
