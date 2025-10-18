Conflicto:
Al intentar fusionar la rama de feature conflicto con main se produjo un conflicto, ya que en ambas ramas se habían editado las mismas líneas, la 21 y la 22, en cambios de notas.
Para resolverlo:
1. Ejecuté `git merge feature-conflicto` desde main
2. Git detectó el conflicto automáticamente
3. Abrí el archivo notas.md con VS Code
4. Localicé los marcadores de conflicto: `<<<<<<<`, `=======`, `>>>>>>>`
5. Eliminé todos estos marcadores
6. Mantuve las notas que consideré
7. Guardé el archivo
8. Ejecuté `git add notas.md`
9. Ejecuté `git commit -m "conflictos resueltos en notas"`
10. Subí los cambios con `git push origin main`