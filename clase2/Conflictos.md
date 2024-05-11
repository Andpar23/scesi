# Conflictos en Git

## Introducción
Cuando dos ramas modifican el mismo archivo en diferentes partes o incluso en las mismas líneas, Git no puede determinar automáticamente qué versión del archivo implementar. Esto crea lo que se conoce como un conflicto.

## Proceso de Fusión
Cuando Git intenta fusionar estas ramas, se da cuenta de que las modificaciones realizadas en una rama entran en conflicto con las modificaciones realizadas en la otra rama. En lugar de tomar una decisión por su cuenta, Git detiene el proceso de fusión y marca el archivo en conflicto.

## Resolución de Conflictos
La resolución de conflictos requiere la intervención del usuario para decidir cómo se deben combinar los cambios. Esto implica editar manualmente el archivo en conflicto para eliminar las partes conflictivas y decidir qué cambios mantener, descartar o modificar.

## Finalización de la Resolución
Una vez que el usuario resuelve manualmente el conflicto y guarda los cambios, Git marca el conflicto como resuelto y permite que continúe el proceso de fusión.

## Importancia
Es importante entender que los conflictos son una parte normal del trabajo colaborativo en un repositorio Git y que saber cómo resolverlos es una habilidad esencial para cualquier desarrollador que trabaje en equipo.
