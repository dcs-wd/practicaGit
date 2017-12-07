# Practica Git
[Daniel Castillo](https://github.com/dcs-wd "Acceso directo a mi GitHub")


### Ejercicio 1

##### 1. ¿Qué comando utilizaste en el paso 11? ¿Por qué?
git reset --hard HEAD~1, porque queriamos dejar el working copy en su estado anterior. Estos solo es posible 	usando el modificador --hard del reset.

##### 2. ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
git reflog y git reset --hard HEAD@{1}, reflog lo use para saber la posición del commit y luego emplee el 	reset --hard para recuperar el archivo como si no hubiera pasado nada.

##### 3. El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
No causó conflicto porque la rama styled contiene ya la rama master.

##### 4. El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
Se creo un conflicto porque en las dos ramas modificamos el archivo en las mismas líneas.

##### 5. El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
No hubo ningun conflicto porque la rama master pertenecia a la rama styled.

##### 6. ¿Qué comando o comandos utilizaste en el paso 25?
`git log --graph --decorate --pretty=oneline`

##### 7. El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
Al encontrarse en el mismo "árbol" y title contener a master podríamos hacer un merge no fastforward sin 	problema.

##### 8. ¿Qué comando o comandos utilizaste en el paso 27?
git reflog y git reset HEAD~1

##### 9. ¿Qué comando o comandos utilizaste en el paso 28?
`git checkout -- git-nuestro.md`

##### 10. ¿Qué comando o comandos utilizaste en el paso 29?
`git branch -D title`

##### 11. ¿Qué comando o comandos utilizaste en el paso 30?
git reflog y git reset --hard e868b16

##### 12. ¿Qué comando o comandos usaste en el paso 32?
`git reset --hard 252990c`

##### 13. ¿Qué comando o comandos usaste en el punto 33?
git reflog y git reset --hard HEAD@{5}
