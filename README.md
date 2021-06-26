# Practica-GIT-y-Github
Práctica 1 del módulo de desarrollo web de keepcoding


# Ejercicio 1
## ¿Qué comando utilizaste en el paso 11? ¿Por qué? 
He utilizado git reset --hard HEAD~1 se usa porque de esta manera deshaces el commit y lo que había en el working copy.

## ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué? 
El comando es reflog para ver todos los commits que habíamos hecho con el objetivo de encontrar el código que identifica el commit borrado. Después he usado git reset --hard b5306ed para volver a ese commit y modificar el working copy.

## El merge del paso 13, ¿Causó algún conflicto? ¿Por qué? 
No ha causado ningún conflicto porque absorbes al "padre"

## El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?  
Sí, ha causado conflicto ya que los archivos git nuestro.md han sido modificados en las mismas líneas y hay que solventar el conflicto.

## El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?  
No ha causado ningun conflicto, es un fast forward.

## ¿Qué comando o comandos utilizaste en el paso 25?  
git log --graph

## El merge del paso 26, ¿Podría ser fast forward? ¿Por qué? 
Podría haberse hecho fast forward para avanzar solamente el puntero al commit hecho en title.

## ¿Qué comando o comandos utilizaste en el paso 27? 
git reset HEAD~1

## ¿Qué comando o comandos utilizaste en el paso 28? 
git restore git-nuestro.md

## ¿Qué comando o comandos utilizaste en el paso 29? 
git branch -D title

## ¿Qué comando o comandos utilizaste en el paso 30? 
Primero git reflog y despues volvemos al merge con git reset --hard e88ba2b

## ¿Qué comando o comandos usaste en el paso 32? 
primero git reflog para saber el identificador del commit inicial y después git reset --hard f0c2b2e

## ¿Qué comando o comandos usaste en el punto 33?
Primero git reflog para saber el identificador del commit final  y después git reset --hard f292548
