# Bem vindo a página de apresentação do GitHub.
## Está página pode ser utilizada como modelo de tutorial ou de apresentação do projeto.

### Comandos de criar projeto
Com o projeto criado no github ir na pasta que se deseja subir um projeto e dar os comandos com o git bash:
     `git init`
     `git add .`
     `git commit -m "first commit"`
     `git remote add origin LINK_DO_PROJETO_APOS_CRIADO_NO_SITE`
     `git push -u origin master`

### Como subir atualizações e baixar atualizações
Todas as atualizações baixadas ou subidas serão feitas apenas na branch atual com os comandos: 
     `git add .`
     `git commit -m "mensagem"`
     `git push`
Este comando básico, serve para unificar todas as alterações realizadas localmente e envia-las ao repositório.
Para baixar os arquivos para o repositório local utiliza-se o comando: 
     `git pull`

### Como criar Branchs
A criação de branchs pode ser feita dentro do site do GitHub ou dentro na pasta do projeto do seu computador através do git bash. 
Indo site do git deve-se criar manualmente digitando o nome para a mesma. Por padrão o projeto já se encontra na branch master (também acontece no caso de se dar clone em projetos).
Através do Git bash dar os comandos:
`git checkout -b  <nome_branch>`
Esse comando cria se não existir ou muda para a branch se já existir(os arquivos da branch também aparecem)
Para apenas alternar entre as branchs usa o comando:
`git checkout <nome_branch>`