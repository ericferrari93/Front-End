# Curso Front-End
#### EBAC

# Git
## Conceitos de Versionamento
 - Histórico
 - Controle de versão
 - Quem alterou
 - O quê alterou
 - Quando alterou
 - Todos os arquivos
 - Evolução contínua
Arquivo A | Versão 1 | Versão 2 Arquivo B | Versão 1 | Versão 2

## Instalação do Git
https://git-scm.com/

 - Windows: https://git-scm.com/download/win
 - Linux (apt-get): sudo apt-get install git
 - Mac (brew): brew install git
## Criar conta no GitHub
## Clonar Projeto
git clone https://github.com/ericferrari93/curso-frontEnd.git

## Commits 
Informações de alteração 
 - Após testado todo seu código
 - git add *
 - git commit -m "mensagem"
 - git push (enviar alterações para o repositório)
 - git pull (puxar / trazer alterações do GitHub para sua máquina)

## GitFlow
Fluxo do Git

### Branchs
São ramificações / versões do código que pode correr de modo paralelos

- main / master (vai para produção, quando o projeto é publicado)
- develop 
- DOD Definition of Done: critérios de aceite
- versionamento 1.0.0

git checkout -b dev (cria uma branch)
git checkout -b main (mudar de branch) 


### Merge
Mescla de versões branchs
Você pode precisar resolver conflitos manualmente

git merge main

### Pull Requests
Mescla de branchs no repositório
Permite code review
O repositório resolve os conflitos automaticamente 

### Configurar o GitFlow
git flow init
git flow feature start {nome-da-feature}
ufaasdaadsa