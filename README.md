# GitFlow
Roteiro passo a passo para utilizar a estratégia GitFlow.

 git init -  Pra inicializar um novo repositorio
 
 git branch develop - Criar branch develop
 
 git push -u origin develop - Para publicar branch local no repositorio remoto

git checkout -b feature/criando-feature-branch -  criar uma brancho e faz chekout nela

git checkout develop -  Para Selecionar a branch develop

git merge feature/criando-feature-branch - Faz o merfe da branch na develop

git checkout develop - Para Selecionar a branch develop

git checkout -b release/0.1.0 -  Para criar uma release

git checkout main -  Seleciona branch master

git merge release/0.1.0 - Faz merge da release/0.1.0  na main

git checkout master - Seleciona branch master