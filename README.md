* ¿Qué comando utilizaste para el paso 11? ¿Por qué?
```Utilize el comando git reset --hard HEAD~1 , porque te permite volver a donde estabas( en este caso un paso atras) y 
descarta los cambios realizados en el working copy.```

* ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
```Uso el comando git reflog para que el ID del commmit al que quiero ir, git reset y el id del commit al que quiero ir y 
git 
restore git-nuestro.md para restaurar los cambios que habia realizado antés.```

* El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
```No, por que no ha habido modificaciones en el archivo git-nuestro.md```

* El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
```Si, hay conflicto por que hay modificaciones en las mismas líneas.```

* El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
```No hay conflicto, styled y main tienen los mismos commit, y no hay modificaciones en el archivo git-nuestro.md```

* ¿Qué comando o comandos utilizaste en el paso 25?
```gìt log --graph```

* El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
```Si podría ser, ya que main y title tienen los mismos commit```

* ¿Qué comando o comandos utilizaste en el paso 27?
```git reset HEAD~1```

* ¿Qué comando o comandos utilizaste en el paso 28?
```git status para ver si había modificaciones, y luego git restore git-nuestro.md```

* ¿Qué comando o comandos utilizaste en el paso 29?
```git branch -D title```

* ¿Qué comando o comandos utilizaste en el paso 30?
```git reflog y git reset con el indentificador que queremos rehacer```

* ¿Qué comando o comandos utilizaste en el paso 32?
```git reflog y git checkout con el id del primer commit```

* ¿Qué comando o comandos utilizaste en el paso 33?
```git reflog y git checkout con el id del commit del titulo```
