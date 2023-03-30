## Adicionando colaboradores no repositório:

- Collaborators
- Add people

## Criando arquivos com o atalho "." (ponto):

- contato.html
- index.html

## Clonando o repositório:

- git clone https://github.com/lucarauj/github-for-teams.git

## Criando branch:

- git checkout -b "nome-da-nova-branch"

## Mudando de branch:

- git checkout "nome-da-outra-branch"

## Adicionando novo arquivo:

- servicos.html

## Adicionando o arquivo para a área de stage e add mensagem de commit:

- git status
- git add .
- git commit -m "add services page"

## Verificando o histórico de commits na branch atual:

- git log

## Alterando a branch e verificando o histórico de commits:

- git checkout main
- git log

## Enviando edições para o repositório:

- git checkout servicesPages
- git push origin servicesPages

## Comando para verificar branch disponíveis:

- git branch
- git branch -a (inclusive as remotas)
- * (asterisco) indica a branch atual

## Comando para atualizar edições entre branch:

- git checkout main
- git merge servicesPages

## Subindo as alterações para o repositório:

- git push origin main

## Excluindo uma branch (local):

- git branch -D servicesPages

## Excluindo uma branch (remoto):

- git push origin --delete servicesPages

## Atualizando branch remoto X local:

- git fetch
- git fetch -p (deleta localmente branch excluídas do repositório)