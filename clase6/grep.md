# Búsquedas con Grep en Git

La herramienta `grep` es una poderosa utilidad de búsqueda que se puede utilizar en Git para buscar patrones específicos en los archivos de un repositorio. Es especialmente útil para realizar búsquedas rápidas y eficientes a través de cualquier árbol en Git, no solo en el directorio de trabajo actual.

## Uso

El comando `git grep` se utiliza para realizar búsquedas en los archivos del repositorio. Puedes especificar un patrón de búsqueda y Git buscará ese patrón en todos los archivos del repositorio.

Por ejemplo, para buscar todas las ocurrencias de la palabra "error" en los archivos del repositorio, puedes ejecutar:
```bash
git grep "error"
