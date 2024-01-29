● ¿Qué comando utilizaste en el paso 11? ¿Por qué?

Utilicé el comando git redet --hard HEAD~1 porque se pedía que se vieran afectados working y stagin area

● ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?

En este caso empleé el reflog para localizar la ID del commit para utilizarlo en git reset <id del commit>

● El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?

Me pidió que guardara los cambios necesarios en pruebas anteriores por lo que opté por usar git add git-nuestro.md para volver a añadir el archivo 

● El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?

Lo mismo que en la pregunta anterior, lo solucioné con git add de nuevo.

PS C:\Users\Yolanda Hernández\Desktop\YolandaHernandezGitPractice> git merge styled
Auto-merging YolandaHernandezGitPractice/git-nuestro.md
CONFLICT (content): Merge conflict in YolandaHernandezGitPractice/git-nuestro.md
Automatic merge failed; fix conflicts and then commit the result.
PS C:\Users\Yolanda Hernández\Desktop\YolandaHernandezGitPractice> git switch styled
fatal: cannot switch branch while merging
Consider "git merge --quit" or "git worktree add".
PS C:\Users\Yolanda Hernández\Desktop\YolandaHernandezGitPractice> git checkout styled
error: you need to resolve your current index first
YolandaHernandezGitPractice/git-nuestro.md: needs merge

● El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
 realmente se ejecuto pero me lanzó este mensaje con un tipo de merge (por defecto) fast forward
Updating 8746410..3f754fc
Fast-forward
 YolandaHernandezGitPractice/git-nuestro.md | 20 ++++++++++----------
 1 file changed, 10 insertions(+), 10 deletions(-)

● ¿Qué comando o comandos utilizaste en el paso 25?

git log --graph --oneline --all

● El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?

El tema del fast forward o no lo entiendo como una manera de visualizar el grafo por lo que entiendo que podría aplicarse de sendas maneras
● ¿Qué comando o comandos utilizaste en el paso 27?

git merge --no-ff title

● ¿Qué comando o comandos utilizaste en el paso 28?

git reset --hard HEAD^

● ¿Qué comando o comandos utilizaste en el paso 29?

git branch -D title desde la rama "master" porque si no me daba error

● ¿Qué comando o comandos utilizaste en el paso 30?

git reset 6cc31ee

● ¿Qué comando o comandos usaste en el paso 32?

git reset a76993d

● ¿Qué comando o comandos usaste en el punto 33?

git reset a635a27
