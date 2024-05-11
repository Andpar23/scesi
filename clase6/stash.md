# Stash

Los stash en Git son una herramienta útil para guardar cambios temporales de forma rápida y temporal. Se utilizan para poder cambiar de rama sin necesidad de realizar commits y sin perjudicar la rama actual.

## Uso

Cuando estás trabajando en cambios en tu directorio de trabajo y necesitas cambiar de rama, pero aún no estás listo para realizar un commit, puedes utilizar el comando `git stash`. Esto guardará tus cambios en un área temporal llamada "stash".

Una vez que hayas cambiado de rama y completado tus tareas en la nueva rama, puedes recuperar los cambios del stash utilizando el comando `git stash pop`. Esto aplicará los cambios guardados del stash a tu directorio de trabajo.

## Beneficios

- **Flexibilidad:** Los stash proporcionan flexibilidad al permitirte guardar temporalmente tus cambios sin necesidad de realizar un commit.

- **Mantener un Directorio Limpio:** Puedes cambiar de rama sin dejar cambios no deseados en tu directorio de trabajo, lo que ayuda a mantener un historial limpio y organizado.

- **Seguridad:** Los stash proporcionan una forma segura de almacenar tus cambios temporales, asegurándote de no perder ningún trabajo importante durante la transición entre ramas.

## Consideraciones

- **Uso Responsable:** Aunque los stash son útiles, es importante usarlos de manera responsable y no abusar de ellos. Recuerda que los stash son temporales y no deben ser utilizados como una solución permanente para evitar realizar commits.

- **Conflicto Potencial:** Si hay cambios en el stash y en la rama actual que entraran en conflicto al aplicar el stash, Git te alertará y deberás resolver estos conflictos manualmente.

- **Recuperación de Stash:** Los cambios guardados en el stash son únicos para cada repositorio local, por lo que si cambias de máquina o eliminas el repositorio local, perderás los stash guardados en ese repositorio.
