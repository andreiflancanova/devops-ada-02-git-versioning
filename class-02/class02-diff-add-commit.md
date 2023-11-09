>## Módulo 02 - Aula 02 - Git Diff-Add-Commit

```bash
git diff --staged
```

```bash
git diff --cached
```

Para adicionar apenas arquivos com a extensão txt a staging area

```bash
git add *.txt
```

Para adicionar todos os arquivos novos do repositório a staging area

```bash
git add -A
```

Para adicionar todos os arquivos dentro de um diretório e suas sub-pastas a staging area

```bash
git add .
```

Desfazer as alterações que foram feitas depois do último commit

```bash
git checkout .
```

Para tirar um arquivo da staging area:

```bash
git rm --cached secret.sql
```

Para tirar uma pasta e todos os arquivos dentro dessa pasta da staging area.
```bash
git rm --cached -rf nome_pasta
```

```bash
git rm --cached -rf nome_pasta
```

Ver logs de informação dos commits
```bash
git log
```

```bash
git log --name-status
```

```bash
git log --pretty=oneline
```

```bash
git log --abbrev-commit
```

```bash
git log --stat
```

Trazer as alterações de forma resumida

```bash
git log -p
```

Trazer os últimos 3 commits
```bash
git log -3
```

Criar atalho para um comando
```bash
git config --global alias.co checkout
```

>### Dotfiles

Dotfiles são arquivos que servem para guardar as configurações do nosso sistema operacional.

Arquivos que começam com "." são arquivos ocultos. 

Um dos exemplos de dotfile é o arquivo .gitignore