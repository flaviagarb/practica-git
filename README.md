## Practica Git & GitHub

**¿Qué comando utilizaste en el paso 11? ¿Por qué?**

Utilicé el comando `git reset --hard HEAD~1`. Para eliminar los cambios en el working copy. 

**¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?**

Utilicé `git reflog` y después `git reset --hard <hash>` para restaurar el commit anterior, ya que pude regresar al hash del commit.

**El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?**

Desde la rama styled hice un `git merge main`. No causó conflicto porque la rama styled contenía ya todos los commits de main. 

**El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?**

Desde la rama styled hice un `git merge htmlify`. Sí causó conflicto ya que el texto del archivo era diferemte y creé un commit que mergeo las dos ramas quedandome con el contenido de la rama styled. 

**El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?**

Hice un `git merge styled` desde la rama main, no causó conflicto porque en el último merge era el mismo commit. 

**¿Qué comando o comandos utilizaste en el paso 25?**

Utilicé el comando: `git log --oneline --graph --decorate --all`. 

**El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?**

Sí, podría ser fast forward porque no hay conflicto. 

**¿Qué comando o comandos utilizaste en el paso 27?**

`git reset --mixed HEAD~1`, para no perder los cambios en el working copy. 

**¿Qué comando o comandos utilizaste en el paso 28?**

`git restore git-nuestro.md`.

**¿Qué comando o comandos utilizaste en el paso 29?**

`git branch -D title`.

**¿Qué comando o comandos utilizaste en el paso 30?**

1. `git reflog` para obtener el hash del commit que contiene el merge.
2. `git reset --hard <hash>` para recuperar el commit del merge. 

**¿Qué comando o comandos usaste en el paso 32?**

`git log` para coger el *hash* y `git checkout <hash>`.

**¿Qué comando o comandos usaste en el punto 33?**

`git checkout main` porque asi volvemos al ultimo commit de main.