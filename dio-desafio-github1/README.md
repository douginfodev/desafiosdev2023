# DESAFIO 1
- Este desafio consiste em criar seu primeiro repositorio no Github e utilizar os comandos que foi aprendidos ao longo do curso.

- Segue abaixo alguns comandos utilizados neste desafio:

$ Comandos Git

git status
Verifica os arquivos que foram modificados ou criados.

git add .
Adiciona todos os arquivos no stage.

git add <nome-do-arquivo>
Envia para o stage um arquivo especifico.

git commit -m"Mensagem do Commit"
Fazer o commit

git commit --amend -m"Alterar a mensagem do commit"

git log
Verifica as informacoes do commit

git reflog
Mostra todo os historico de logs do commit

Remover todos os arquivos do git
rm - rf .git

git restore <nome-do-arquivo>
Retorna o arquivo a uma posicao anterior.(meio que um ctrl-z)

git reset --soft(volta com os arquivo para o stage)
          --mixed(volta para a arvore)
          --hard(volta tudo ao normal) <id-hash-do-commit>
retorna ao commit especifico

git restore --staged <nome-do-arquivo>
remove um arquivo especifico da stage area

BRANCH
git branch
git branch --list
Listar todas as branchs

git branch -a
Lista os branchs remoto.

git branch -v
Mostra os ultimos commits de cada branch

git branch -d <bone-da-branch>
Mostra os ultimos commits de cada branch

git fetch origin main
Clone e merge repositorio

git merge origin/main

git merge <nome-da-branch-mergeada>
Fazer a merge das branchs

git branch -m master main
alterar as branchs

git checkout -b <nome-da-branch>
Criar uma nova branch

git checkout <nome-da-branch>
Movimentar entre as branchs

git push -u origin main
vrian uma branch mais na area remota

git remote add origin https://github.com/douginfodev/projetosdio
Linkar meu repositorio local com o repositorio no git hub

git push -u origin main


