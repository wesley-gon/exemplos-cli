# Principais comandos git

## inicializar repositorio
`git init`

## Adicona o arquivo ao git (coloca stash)
`git add nome-arquivo`

## Adicona vários arquivos ao git (coloca na memória)
`git add .`

## Mostra o Status geral de uso do GIT
`git status`

## Mostra o hisórico de Commit
`git log`

## Realizar o commiti com uma menssagem
`git commit -m "mensagem desejada"`

## Mudar o nome da branck de master para mains (basta apenas uma vez no inicio)
`git branch -M main`

## fazer um push (envio) para o repositótio remoto  (o "-u" é necessário somente na primeira conexão)
`git push -u origin main`

## Fazer clone de um repositório 
`git clone endereço-repositorio.git`

## Adicione uma referência do repositório remoto no ambiente local (somente uma vez)
`git remote add origin endereço-repositório.git`

## Para mais informações de comando:
https://training.github.com/downloads/pt_br/github-git-cheat-sheet/

## Recuperar o histórico do repositório de remoto
`git pull`