# Respuestas práctica git
## *Jorge Sánchez Dabaliña*

## - ¿Qué comando utilizaste en el paso 11? ¿Por qué?
` $ git reset --hard HEAD~1`

Reseteamos el commit con git reset ultilizando --hard para que el reseteo afecte también a la working copy.

## - ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
`$ git reflog` 
	`$ git reset ("tag del estado anterior")`
		`($ git checkout -- *.md)`
    
Con el primer comando se nos despliega una lista de estados con sus respectivos tags, con el tag y el comando reset llegamos hasta donde deseemos, por último vacíamos la working copy para dejarlo todo en el estado inicial.
		
## - El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?

No, porque la rama master estaba por detrás de styled en commits.

## - El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?

Si, porque tanto htmlify como styled estaban creadas a partir de master

## - El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
No, porque la rama master estaba por debajo en commits

## - ¿Qué comando o comandos utilizaste en el paso 25?

`git log --graph`

## - El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?

No, habría generado un conflicto porque title estaba por encima de master.

## - ¿Qué comando o comandos utilizaste en el paso 27?
`$ git reset HEAD~1`

## - ¿Qué comando o comandos utilizaste en el paso 28?
`$ git checkout -- *.md`

#### - ¿Qué comando o comandos utilizaste en el paso 29?

`$ git branch -D title`

## - ¿Qué comando o comandos utilizaste en el paso 30?
`$ git reflog` 
	`$ git checkout ("tag del punto anterior al reset") `

## - ¿Qué comando o comandos usaste en el paso 32?
`$ git reflog` 
	`$ git checkout ("primer tag") `

## - ¿Qué comando o comandos usaste en el punto 33?

`$ git reflog` 
	`$ git checkout ("tag del estado ")`

