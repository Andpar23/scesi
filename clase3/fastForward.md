# Fast Forward

El "fast forward" es una operación de fusión en Git que ocurre cuando se integran los cambios de una rama en otra sin crear un nuevo commit de fusión. Esto sucede cuando los commits de la rama que se está fusionando pueden aplicarse directamente sobre la punta de la rama en la que se está fusionando, creando una línea de commits lineal y sin ramificaciones.

## Funcionamiento
Cuando ejecutas `git merge <rama>` y Git determina que puede realizar una fusión "fast forward", simplemente avanza el puntero de la rama hacia adelante hasta el último commit de la rama que se está fusionando. Esto significa que la rama en la que te encuentras ahora apunta al mismo commit que la rama que estás fusionando, y no se crea un nuevo commit de fusión.

## Ventajas
El "fast forward" es una operación rápida y simple, ya que no crea un nuevo commit de fusión ni requiere la resolución de conflictos. Ayuda a mantener un historial de commits limpio y lineal, especialmente en situaciones donde las ramas están bien sincronizadas y no hay conflictos entre los cambios.

## Uso
El "fast forward" es la forma predeterminada de fusión en Git cuando es posible realizarla. Sin embargo, en algunos casos, como cuando se desea mantener un historial de commits más explícito o cuando se desea evitar la pérdida de información sobre la relación entre las ramas, se puede optar por deshabilitar el "fast forward" utilizando la opción `--no-ff` al fusionar (`git merge <rama> --no-ff`).

