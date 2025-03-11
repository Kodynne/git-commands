## Como clonar um repositório 

Passo a Passo:

```bash
# NAvegando até o disco C
cd /c

#Criando um repositório
mkdir minha-pasta

#Entrando na minha pasta
cd minha-pasta
#Clonando o repositorio
git clone <link-repositorio>

#Acessando o repositório
cd <path-repositorio>

## Informação importante

Quando você salva um repositório em staged changes, ele salva uma "foto", e o arquivo original continua em stage changes.

##Verificar status
git status

##adicionar pasta
git add README.md

##abrir vscode
code .

##salvar no repositorio local
git commit -m 'Nomear commit'

##Salvar no git
git push origin 'Nome da Branch'

## minha empresa

1 - setup
2 - Baixar o GIT