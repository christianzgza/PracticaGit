- ¿Qué comando utilizaste en el paso 11? ¿Por qué?
git reset --hard HEAD~1
reset HEAD~1 para volver al commit anterior y --hard para perder los cambios.

- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
git reflog y git reset --hard <id_commit>
Primero se busca el identificador del commit perdido y después se regresa a él rehaciendo los cambios desechos en el punto anterior con su id.

- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué? 
No, porque están el línea.

- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
Sí,  porque el mismo archivo, tiene diferencias en algunas líneas, lo que provoca un no fast-forward.

- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
No, master está en línea.

- ¿Qué comando o comandos utilizaste en el paso 25?
git config alias.graph "log --decorate --graph --pretty=oneline"
git graph
He configurado un alias primero para facilitarme la vida y después lo he ejecutado.

- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
Sí, están en línea.

- ¿Qué comando o comandos utilizaste en el paso 27? 
git reset HEAD~1

- ¿Qué comando o comandos utilizaste en el paso 28?
git checkout -- git-nuestro.md

- ¿Qué comando o comandos utilizaste en el paso 29?
git branch -D title

- ¿Qué comando o comandos utilizaste en el paso 30?
git reflog (para tomar el id del commit)
git reset --hard <id_commit> (Entendiendo el enunciado como que se quiere rehacer el merge incluyendo los cambios)

- ¿Qué comando o comandos usaste en el paso 32? 
git reset HEAD~3
git checkout -- git-nuestro.md

- ¿Qué comando o comandos usaste en el punto 33?
git reflog (para tomar el id del commit)
git reset --hard <id_commit>
git checkout -- git-nuestro.md

Alumno: Cristian Espes
