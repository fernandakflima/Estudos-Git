# Estudos | Git

Repositório para documentar os estudos de Git.

## 📚 Documentação
- [Documentação Git](https://git-scm.com/doc)
- [Documentação GitHub](https://docs.github.com/pt)

## 💻 Notas e Resumos
| Comando | Descrição |
|---------|-----------|
| cat config | cat mostra todo o conteúdo do diretório|
| git clone URL| para clonar um repositório remoto|
| git remote -v | mostra os repositórios remotos que você esta vinculado|
| git remote add | adiciona repositório remoto|
| touch | cria um arquivo vazio|
| echo nome do arquivo .gitignore | esconde o arquivo que você não quer mostrar|
| git restore | restaura a versão anterior do arquivo|
| git commit --amend -m"menssagem" | edita a menssagem do commit anterior|
| git reset --soft | pega o resch do último commit e volta para a área de preparação|
| git reset --mixed | pega os arquivos do último commit e coloca na área de trabalho, onde os arquivos ainda não são rastreados |
| git reset --hard | Ignora os arquivos do commit anterior e desfaz eles |
| git reflog | visão mais detalhada dos commits |
| git reset nome-do-arquivo | exclui o arquivo |
| git restore --staged nome-do-arquivo| exclui o arquivo |
|git pull | vai puxar as informações do repositório remoto e mesclar com as informações do repositório local |
| git checkout -b nome-da-branch| cria uma nova branch |
| git checkout nome-da-branch | entra na branch desejada |
| git branch -v | mostra os commits de cada branch |
| git merge nome-da-branch | mescla as branchs |
| git branch | lista as branchs existentes |
| git branch -d nome-da-branch | exclui a branch | 
| git fetch | baixa o repositório remoto para o local |
| git diff | mostra as diferenças de arquivos entre um repositório e outro |
| git merge | mescla as alterações |
| git clone URL  --branch nome-da-branch --single-branch | clona apenas o repositório daquela branch |
| git stash | arquivos modificados |
| git stash list | lista as modificações arquivadas |
| git stash pop | traz as alterações de outra branch e exclui as alterações mais recentes da pilha |
|git stash apply | para manter a alteração |
