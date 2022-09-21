# Cuestionario

A) ¿Qué comando utilizaste en el paso 11? ¿Por qué?  

> `git reset --hard HEAD~1`

> Porque habia que eliminar todo el commit sin dejar nada en el working copy

B) ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?    

> 'git reset --hard f8f74c1'

> Para recuperar el commit anteriormente eliminado

C) El merge del paso 13, ¿Causó algún conflicto? ¿Por qué? 

> No, porque la rama styled ya contiene el comit de la rama main. Styled esta más arriba que main.

D) El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?

> Si, porque los archivos a juntar son diferentes, uno es un texto normal y el otro es html.

E) El merge del paso 20, ¿Causó algún conflicto? ¿Por qué?

> No, porque el main se encuentra abajo del styled.

F) El merge del paso 24, ¿Podría ser fast forward? ¿Por qué? 

> No, porque el commit del que nacen solo tiene es modificación.

G) ¿Qué comando o comandos utilizaste en el paso 25?  

> 'git reset HEAD~1'

H) ¿Qué comando o comandos utilizaste en el paso 26?  

> 'git checkout -- don-quijote.md'

I) ¿Qué comando o comandos utilizaste en el paso 27?  

> 'git branch -D title'

J) ¿Qué comando o comandos utilizaste en el paso 28?  

> 'git merge 760b42c'

K) ¿Qué comando o comandos utilizaste en el paso 30? 

> 'git tag title'