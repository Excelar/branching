¿Por qué en esta rama!? Porque no!?

Esto es un pequeño tutorial de todo lo que hice para armar este pequeño arbolito! 
**1)Crear el repositorio(el cual nombre "branching")**
>>*En mi github personal cree un nuevo repositorio
>>*Con la creación arme el primer commit en el master 	
**2)Cree la "rama1" la cual sería que seguiría del master**
>>*(En master)git branch rama1
>>*git checkout rama1
>>*(crear un archivo y hacer commit)git commit 
>>*(pushear)git push
**3)Cree la "rama2" la cual tendrá este tutorial**
>>*(crear rama2)git branch rama2
>>*(moverse a esta rama)git checkout rama2
>>*(commitear para finalizar la creación)git commit
>>*(pushear)git push
**4)Cree la "rama3" la cual será posteriormente "mergeada" con la rama1**
>>*(crear rama3)git branch rama3
>>*(moverse a esa rama)git checkout rama3
>>*(commitear)git commit
>>*(pushear)git push
**5)Cree la "rama4" la cual sera simplemente una rama mas que quedará** 
>>*(crear)git branch rama4
>>*(moverse)git checkout rama4
>>*(commit)git commit
>>*(pushear)git push
**6)Hacemos merge de las ramas 1(rama1) y 3(rama3)**
>>*(nos ubicamos en la rama1 que es la que va a quedar atras en el merge)git checkout rama1
>>*(ahora usamos merge para que la rama pase estar siguiendo la rama1)git merge rama3

Soy Juan Manuel, esto fue Branching para la consola GIT, espero que les haya gustado, CHAU!
