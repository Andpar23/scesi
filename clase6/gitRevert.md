# Revertir Cambios con Git Revert

El comando `git revert` en Git se utiliza para revertir los cambios introducidos por un commit específico, creando un nuevo commit que deshace los cambios realizados por el commit original. A diferencia de otros métodos, `git revert` es un método no destructivo que preserva el historial del repositorio.

## Uso de git revert

Para revertir los cambios introducidos por un commit específico, puedes utilizar el siguiente comando:

```bash
git revert <identificador_commit>

## Beneficios de `git revert`

- **No Destructivo:** A diferencia de `git reset`, que modifica el historial del repositorio, `git revert` es un método no destructivo que crea un nuevo commit para revertir los cambios introducidos por el commit original. Esto ayuda a preservar la integridad del historial del repositorio.

- **Historial Claro:** Cada vez que utilizas `git revert`, se crea un nuevo commit que deshace los cambios introducidos por el commit original. Esto proporciona un historial claro y detallado de todas las operaciones de reversión realizadas en el repositorio.

- **Revertir Múltiples Commits:** Puedes utilizar `git revert` para revertir los cambios introducidos por múltiples commits, especificando una lista de identificadores de commits separados por espacios.

### Consideraciones

- **Conflictos de Fusión:** Al revertir cambios, puede haber conflictos de fusión si los cambios revertidos entran en conflicto con cambios posteriores en el historial del repositorio. Deberás resolver estos conflictos manualmente antes de finalizar la operación de revertido.

- **Comentarios de Commit:** Es recomendable incluir comentarios descriptivos al realizar el revertido utilizando `git revert`, para mantener un registro claro de los motivos y las operaciones realizadas.
