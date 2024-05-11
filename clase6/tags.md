# Etiquetas (Tags)

Las etiquetas, conocidas como tags en inglés, son punteros estáticos que se asocian con un commit específico en Git. Se utilizan típicamente para marcar versiones de lanzamiento importantes en un repositorio, proporcionando una forma rápida y conveniente de referenciar puntos específicos en la historia del proyecto.

## Uso

Para crear una etiqueta en Git, se utiliza el comando `git tag`, seguido del nombre de la etiqueta y el hash del commit al que se desea asociar la etiqueta. Por ejemplo:
```bash
git tag v1.0 1a2b3c4d
