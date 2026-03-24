Diferencia entre merge y rebase

git merge une ramas creando un commit de merge, manteniendo el historial real.
git rebase reescribe la historia moviendo commits para que parezcan lineales.

 Cuándo usar cada uno

Usaría rebase:
- Para mantener un historial limpio antes de integrar cambios.

Usaría merge:
- Cuando trabajo en equipo y no quiero reescribir historial.

 Por qué no usar rebase en ramas compartidas

Porque reescribe commits cambia hashes y puede causar conflictos y problemas
a otros desarrolladores que ya hayan trabajado sobre esos commits.
