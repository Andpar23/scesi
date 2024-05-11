# Comando: `git clone <link>`

El comando `git clone <link>` se utiliza para clonar un repositorio Git desde un enlace remoto a tu máquina local. Esto crea una copia local del repositorio remoto, incluyendo todas las ramas y el historial de commits.

## Uso
Al ejecutar `git clone <link>`, Git creará un directorio nuevo con el nombre del repositorio y descargará todos los archivos y la historia de commits desde el repositorio remoto especificado por `<link>`.

## Acceso a Otras Ramas
Después de clonar un repositorio, por defecto estarás en la rama principal del repositorio (generalmente `main` o `master`). Sin embargo, puedes acceder a otras ramas existentes utilizando el comando `git checkout <rama>`.

Por ejemplo, si deseas cambiar a una rama llamada `feature-x`, puedes hacerlo con el siguiente comando:
git checkout feature-x

css
Copy code

Esto te llevará a la rama `feature-x`, donde podrás ver y trabajar en los archivos y commits asociados a esa rama.

## Consideraciones
- Es importante tener en cuenta que al cambiar a una nueva rama con `git checkout <rama>`, tu directorio de trabajo se actualizará para reflejar el estado de esa rama.
- Antes de cambiar a otra rama, asegúrate de guardar y confirmar cualquier cambio que tengas en la rama actual para evitar pérdida de datos.
