*¿Qué comando utilizaste en el paso 11? ¿Por qué?*
- `git reset --hard HEAD~1 ` Porque quería deshacer los cambios en Working 
Copy y Graph

*¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?*
-`git reset --hard 0043d80` Para poder volver a ese commit

*El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?*
-No, porque ya estaban las dos ramas en el mismo commit.

*El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?*
-Sí hay conflicto porque hay cambios en las mismas líneas

*El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?*
-No hay conflicto porque no hay distintos cambios en las mismas líneas y 
además es fast-forward

*¿Qué comando o comandos utilizaste en el paso 25?*
- `git log --oneline`

*El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?*
- Sí, porque main y title están ya en la misma rama

*¿Qué comando o comandos utilizaste en el paso 27?*
- `git restore main`Para que solo afecte al working copy.

*¿Qué comando o comandos utilizaste en el paso 28?*
-`git reset --hard c613fc8`

*¿Qué comando o comandos utilizaste en el paso 29?*
- `git branch -D title`

*¿Qué comando o comandos utilizaste en el paso 30?*
-`git reset --hard 24cbd66`

*¿Qué comando o comandos usaste en el paso 32?*
- `git reset --hard c613fc8`

*¿Qué comando o comandos usaste en el punto 33?*
-`git reset --hard 4b559db`

