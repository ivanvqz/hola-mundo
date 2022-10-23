## Creación de otros branches
    git switch -c <nombre-branch>
Crea,  a la vez que nos cambia en el nuevo branch, el branch con el nombre indicado. Para cambiarnos de branch solo basta con quitar el -c.
## integrar los cambios en el flujo principal
    git merge <nombre-branch>
Para hacerlo, primero debemos de ubucarnos en el flujo principal, es decir, en el branch master. Una vez allí, ejecutamos el comando anterior. Si no hay conflictos, se integrarán los cambios en el flujo principal. Si hay conflictos, se nos indicará que los resolvamos y luego ejecutamos el comando anterior.