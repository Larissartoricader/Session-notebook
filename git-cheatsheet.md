# Git CheatSheet

## Temas

1. Como criar
2. Como deletar
3. Ligar Git Github
4. Alteracoes no GIT/GitHUB

## Básico Git

### Como criar um GIT?

1. Evitar criar um GIT dentro de um GIT. Certifique-se que nao há nenhum git-parents.
2. Crie uma pasta `mkdir nome-da-pasta``
3. Entre na nova pasta `cd nome-da-pasta ``
4. Crie um documento dentro da pasta `touch README.me`
5. Transformar a pasta em GIT `git init`

### Como deletar um GIT local?

1. Entre no Directory que contem o GIT-Repository que deseja deletar.
2. Use o comando para deletar o GIT `rm -rf <nome-do-git>`

## Como conectar o Git ao Github?

1. Certifique-se que já existe m GIT local
2. Crie um repository no Github
3. Ao finalizar a criacao, use o link de criacao do Repository do Github no terminal. `git remote add origin git@github.com:<username>/<reponame>.git`<- Esse link será encontrado dentro do novo repository.
4. No terminal, voce enviara os aquivos do Git local para o Git no Github através do comando: git push -u origin main. Certifique se voce se encontra dentro do repositorio GIT no terminal.

### Como enviar alteracoes para o GIT local

1. Após salvar as alteracoes no software, inclua essas alteracoes no git. `git add --all` Se necessário, é possível selecionar também aquivos especificos pelo nome do arquivo.
2. Envie a alteracao adicionada para o Commit `git commit -m "um comentário breve"`
3. Faca o Upload dessas alteracoes no Github `git push`

### Como criar um BRANCHE

1. Certifique se voce esteja dentro do Git-Repository no Terminal.
2. Digite o comando que nao só cria mas também automaticamente já entra nesse Branch `git switch -c nome-do-branch `
