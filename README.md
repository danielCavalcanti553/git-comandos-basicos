# Comandos Básicos

## Git
Download
https://git-scm.com/downloads

## Controle de versão
https://git-scm.com/book/pt-br/v1/Git-Essencial-Obtendo-um-Reposit%C3%B3rio-Git

## Noções Básicas de Git
https://git-scm.com/book/pt-br/v1/Primeiros-passos-No%C3%A7%C3%B5es-B%C3%A1sicas-de-Git

## Alguns Comandos Windows
cd c:/pasta Selecionar pasta

cd .. Retornar pasta anterior

ls -la  Visualizar arquivos e pastas

ls visualizar arquivos

mkdir nomePasta Criar pasta

## Configurações Iniciais Git
Configuração usuário local

git config --global user.email "seu email"

git config --global user.name "seu nome"

## Verificar usuário
git config user.email

git config user.name

## Vefificar Todas as Configurações

git config user.email

git config user.name

## Inicializando Diretório

git init
Verificando Status dos Arquivos

git status
Adicionando arquivos

git add index.html

git add .

## Executando Commit

git commit -m "Primeiro Commit"

## Visualizando Commits

git log

git log --graph

## Pesquisar commits por autor

git log --author="daniel"


## Visualizar alterações por autores

git shortlog

## Visualizar alterações em um commit
git show {id Commit}

git show 2c42f4e45651e1313412b869912703d3330dd451

## Visualizar alterações antes de executar um commit

git diff

git diff --name-only (visualiza por arquivos)

## Retirar arquivo do storage
git reset arquivo.txt

## Resetando Commits
git reset HEAD~1

## Reset Hard
git reset --hard HEAD~1

## Reverter um Commit Específico
git revert 2c42f4e45651e1313412b869912703d3330dd451

## Adicionando Repositório Remoto
git remote add origin ENDEREÇO REPOSITÓRIO (GIT HUB)

git remote add origin https://github.com/danielCavalcanti553/teste.git

## Removendo Repositório Remoto

git remote rm origin

## Enviando para repositório

 git push -u origin master
