# Perca o medo do Git

## Instalar o git
Instruções de instalação: https://git-scm.com/book/pt-br/v2/Come%C3%A7ando-Instalando-o-Git


* `git init` Cria repositório
* `git add` Adiciona arquivos
* `git status` Mostra mudanças que serão commitadas
* `git log` Mostra histórico de commits
* `git commit` Cria um "checkpoint" no tempo com as mudanças feitas no arquivo
* `git config --global core.editor nano` Muda o editor de texto para Nano (configuração global na sua máquina)
* `git branch` Lista todgit branchas as branches existentes
* `git branch nome-da-branch` Cria nova branch chamada nome-da-branch
* `git checkout nome-da-branch` Troca de branch
* `git checkout -b nome-da-branch` Cria novo branch chamado nome-da-branch e troca para o branch nome-da-branch
* `git diff` Vai mostrar as diferenças no arquivo em relação ao commit anterior
* `git add nome-do-arquivo` Vai colocar o arquivo em stage, para que as mudanças sejam commitadas
* `git add -A` ou `git add .` Adiciona todos os arquivos do projeto para stage
* `git add -i` Abrir o menu interativo do git add (retirar arquivos de stage, colocar novos arquivos)
* `git merge nome-do-branch` Vai mergear nome-do-branch dentro do branch atual
* `git rebase nome-do-branch` Vai mudar o head do Branch atual para o HEAD do nome do branch
* `git merge --abort` Vai abortar o merge quando tiver conflito
* `git diff --check` Vai te mostrar todos os arquivos e as linhas que estão com conflito
* `git merge --continue` Vai continuar o merge depois que os conflitos forem resolvidos e os arquivos adicionados para stage
* `git rebase -i` Abrir a janela de rebase interativo que possibilita que você mude a história do projeto
* `git rebase --abort` Vai abortar o rebase em caso de conflito
* `git rebase --continue` Vai continuar o rebase depois que os conflitos forem resolvidos e os arquivos adicionados para stage
* `git remote add origin https://github.com/andresionek91/LIVE-002---Perca-o-medo-do-Git.git` Linka o repositório local com o repositório remoto
* `git push -u origin master` Vai subir o branch master para a origin (repositório remoto /GitHub)
* `git push` Vai subir as suas alterações do repositório local para o repositório remoto
* `git pull` Vai baixar as alterações do repositório remoto para o local
