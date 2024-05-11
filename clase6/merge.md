# Merge

El comando `git merge` se utiliza para fusionar dos ramas en Git. Git cuenta con varias estrategias de fusión y evalúa automáticamente cuál es la más conveniente. Sin embargo, pueden surgir conflictos si hay modificaciones dispares en la misma porción de un archivo en ambas ramas que se están fusionando. En tales casos, Git no puede fusionar automáticamente los cambios y se produce un conflicto que debe ser resuelto manualmente.

## Estrategias de Fusión

Git evalúa automáticamente cuál es la estrategia de fusión más adecuada para las ramas que se están fusionando. Algunas de las estrategias comunes incluyen:

- **Merge Fast-Forward:** Si la rama que se está fusionando tiene todos los commits accesibles desde la rama actual, Git realizará una fusión fast-forward, donde simplemente moverá la punta de la rama actual hacia adelante sin crear un commit de fusión.

- **Fusión Automática:** Si las ramas tienen cambios divergentes pero pueden fusionarse automáticamente, Git creará un nuevo commit de fusión que combina los cambios de ambas ramas.

- **Fusión Manual:** Si hay conflictos entre los cambios en las ramas que no pueden resolverse automáticamente, Git detendrá el proceso de fusión y marcará los archivos en conflicto. En este caso, se requiere una intervención manual para resolver los conflictos.

## Resolución de Conflictos

Cuando se produce un conflicto de fusión, Git indica las diferencias entre las ramas y marca los archivos en conflicto. Para resolver el conflicto, se deben editar manualmente los archivos en conflicto, eliminando las marcas de conflicto (`<<<<<<<`, `=======`, `>>>>>>>`) y conservando las partes deseadas de cada rama.

Una vez que se resuelve el conflicto, se debe realizar un commit para finalizar el proceso de fusión. Es importante proporcionar detalles claros sobre cómo se resolvió el conflicto, a menos que sea obvio.

## Uso de Mergetool

En algunos casos, Git puede lanzar una herramienta de resolución de conflictos, conocida como mergetool, para ayudar en la resolución manual de conflictos. Esta herramienta proporciona una interfaz gráfica para comparar y fusionar cambios conflictivos en archivos.

