# Git-Github 

[CLI] => Command line interface

suponete en este ejemplo
[10:55 AM]
que te di recien, podrias haber tirado 3 ramas por lo menos
[10:55 AM]
1) [3ramas] main, dev-tomi, fixedEjemplo.js
[10:56 AM]
entonces (ya teniendo codigo en main y dev-tomi): creas efectivamente la rama fixedEjemplo.js le tiras un pull de dev-tomi (edited)
[10:56 AM]
paso siguiente? mergeas dev-tomi con fixedEjemplo.js
[10:56 AM]
por ultimo, mergeas dev-tomi con main
[10:56 AM]
es como una escalera de cambios
[10:56 AM]
eso te van a evaluar
[10:56 AM]
que sepas ir moviendo cambios pequeños a travez de tu arbol de trabajo

## Git Commands

[pull] => The opposite of push => Download changes from remote repo to your local machine.
`Basically you PULL changes` 

[status] => Me muestra todo aquello que fue created, upadate or deleted pero aun no ha sido commited.

 git remote add origin [gitLinkCopied]
 git remote -v => [comprobasVerison] 
 git push origin master => Para que se vuelval el spot default del push => git push **-u** origin master


## Git branching

1) At first the code in master and the [branch] => `Will be exactly the same` => A medida que vas codeando en la feature branch => those changes are only seen in this feature branch.
Todos los changes y commits en esa feature branch son ppios de esa Branch! => **When you switch up to the master branch you wont be able to see those changes**

**commands**: 
1. git checkout [-b] [branchName]
2. git branch => `Let you know in what branch you standing`
3. get checkout [branchName] => `Moves you to [branchName] u picked`