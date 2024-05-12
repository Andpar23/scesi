# Comando: `git push`

El comando `git push` se utiliza para enviar los cambios locales de una rama a un repositorio remoto. Esto actualiza el estado del repositorio remoto con los commits realizados en la rama local.

## Uso
Cuando ejecutas `git push`, Git enviará los commits de la rama actual al repositorio remoto predeterminado, que suele ser denominado `origin`. Es importante tener en cuenta que los cambios enviados con `git push` son públicos y afectarán a otros colaboradores que trabajen en el mismo repositorio remoto.

## Comando: `git push -u origin <rama>`

La opción `-u` (o `--set-upstream`) se utiliza para configurar la rama local para hacer seguimiento de la rama remota especificada. Esto significa que en futuros `git push` y `git pull`, Git sabrá automáticamente a qué rama remota y local hacer referencia, evitando tener que especificar la rama y el repositorio cada vez.

Por ejemplo, al ejecutar `git push -u origin main`, se envían los commits de la rama `main` al repositorio remoto `origin`, y la rama local `main` se configura para hacer seguimiento de la rama remota `main`.

## Consideraciones
- Antes de ejecutar `git push`, es importante asegurarse de que los cambios locales estén correctamente organizados y listos para ser compartidos con otros colaboradores.
- Es una buena práctica utilizar la opción `-u` al hacer el primer `git push` de una nueva rama para establecer el seguimiento de la rama remota.

