# Ours and Theirs

## Comando: `git merge -s ours <rama>`

Este comando fusiona la rama especificada `<rama>` en la rama actual, conservando los cambios de la rama actual en caso de conflictos. Si hay conflictos durante la fusión, se priorizan los cambios de la rama actual sobre los de la rama especificada. Es útil cuando se quiere mantener la dirección de la rama actual y desechar los cambios de la otra rama en caso de conflicto.

## Comando: `git merge -s theirs <rama>`

Este comando fusiona la rama especificada `<rama>` en la rama actual, conservando los cambios de la rama especificada en caso de conflictos. Si hay conflictos durante la fusión, se priorizan los cambios de la rama especificada sobre los de la rama actual. Es útil cuando se quiere aceptar los cambios de la otra rama y desechar los de la rama actual en caso de conflicto.

