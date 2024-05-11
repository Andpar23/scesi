# Comando `git branch nomRama`

Este comando se utiliza en Git para crear una nueva rama con el nombre especificado. 

Al ejecutar `git branch nomRama`, se crea una nueva rama llamada `nomRama`. Esta rama comenzará desde el mismo punto en el que te encuentras actualmente en tu repositorio, lo que significa que contendrá exactamente los mismos commits que la rama desde la que se creó.

Crear una nueva rama con `git branch` es útil cuando deseas desarrollar una nueva característica o trabajar en una tarea específica sin afectar al código de la rama principal (generalmente la rama `master` o `main`). Una vez que hayas completado tu trabajo en la nueva rama, puedes fusionarla de vuelta en la rama principal utilizando el comando `git merge`.

Es importante tener en cuenta que la creación de la rama con `git branch` no cambia la rama actual en la que te encuentras; simplemente crea una nueva rama y continúas en la rama actual. Para cambiar a la nueva rama, puedes usar el comando `git checkout nomRama` o `git switch nomRama`.

Recuerda que es una buena práctica dar nombres descriptivos a tus ramas para que sea más fácil entender su propósito. Por ejemplo, podrías nombrar una nueva rama como `feature/nueva-caracteristica` para indicar que estás trabajando en una nueva característica específica.

¡Y eso es todo sobre el comando `git branch nomRama`!
