# No Fast Forward

El "no fast forward" es una opción que se puede utilizar al fusionar ramas en Git para integrar los cambios de una rama en otra de una manera que preserve la estructura de la historia de los commits, incluso si no es necesario resolver conflictos.

## Funcionamiento
Cuando ejecutas `git merge <rama> --no-ff`, Git realiza una fusión que resulta en la creación de un nuevo commit de fusión, incluso si los cambios podrían haberse aplicado directamente sobre la punta de la rama actual sin crear una bifurcación.

## Propósito
El propósito principal de utilizar el "no fast forward" es mantener una estructura de historial de commits más explícita y preservar información sobre la relación entre las ramas. Al crear un nuevo commit de fusión, se mantiene un registro claro de cuándo y dónde se realizaron las fusiones, lo que puede ser útil para comprender la evolución del proyecto a lo largo del tiempo.

## Ventajas
- **Claridad en el historial:** Los commits de fusión creados mediante "no fast forward" proporcionan una representación explícita de dónde se integraron los cambios de una rama en otra, lo que facilita la comprensión del historial del proyecto.
- **Preservación de la estructura:** Al mantener una estructura de historia de commits más lineal y sin rebases, se conserva la información sobre la secuencia en la que se desarrollaron las características y se realizaron las fusiones.

## Uso
El "no fast forward" se puede utilizar cuando se desea preservar la estructura del historial de commits y se prefiere tener una representación más clara de las fusiones en el historial del repositorio. Se puede activar agregando la opción `--no-ff` al comando `git merge <rama>`.

