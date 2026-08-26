# practicas-git-github

**Estudiante:** Jan Ariza
**Asignatura:** Buenas Prácticas de Desarrollo de Software - Remoto-25376
**Universidad:** Universidad de la Costa
**Semestre:** 4to semestre

## Descripción del proyecto

Repositorio de práctica para el flujo de trabajo con Git y GitHub: creación y gestión
de ramas (`main` y `prod`), registro de cambios mediante commits, apertura de un
Pull Request de `prod` hacia `main`, generación y resolución intencional de un
conflicto entre ramas, y finalización del proceso mediante el merge del Pull Request.

## Flujo realizado

1. Se creó la rama `prod` a partir de `main`.
2. Se agregó el archivo `version.txt` en `prod` con un valor distinto al de `main`.
3. Se subió la rama `prod` a GitHub y se comprobó que los archivos cambian al alternar entre ramas.
4. Se creó un Pull Request de `prod` hacia `main`.
5. Se modificó `version.txt` directamente en `main` para provocar un conflicto real con `prod`.
6. Se resolvió el conflicto desde el editor web de GitHub, conservando la versión de `main`.
7. Se completó el merge del Pull Request hacia `main`.
8. Se confirmó el historial final del repositorio con `git log --oneline --graph --all`.
