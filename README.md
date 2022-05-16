# Estudos Git/GitHub

## Comandos Básicos

[Documentação Oficial Git](https://git-scm.com/docs/git/pt_BR)

```bash

# Inicialização de Repositório
# https://git-scm.com/docs/git-init

git init

# Adicionar arquivos ou diretórios ao repositórios
# https://git-scm.com/docs/git-add

git add <'nome_do_arquivo'>
git add . 
git add -A
git add *

# Referência o repositórios local com o remoto
# https://git-scm.com/docs/git-remote

git remote add origin <'url_do_repositório_remoto'>

# Verificar status do repositório local
# https://git-scm.com/docs/git-status

git status

# Empurra alterações do repositório local para o remoto
# https://git-scm.com/docs/git-push

git push origin main
git push # Forma simplificada

# Puxa alterações do repositorio remoto para o local
# https://git-scm.com/docs/git-pull

git pull origin main
git pull # Forma simplificada

# Clona um repositorio remoto maquina local
# https://git-scm.com/docs/git-clone

git clone <'url_do_repositório_remoto'> 

# Criando Tag
# https://git-scm.com/book/pt-br/v2/Fundamentos-de-Git-Criando-Tags

git tag -a v1.0 -m "Versão 1.0"

# Lista as Tag

git tag

# Enviar a Tag para host

git push origin v1.0


```
