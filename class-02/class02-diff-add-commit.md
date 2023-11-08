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

>### Dotfiles

Dotfiles são arquivos que servem para guardar as configurações do nosso sistema operacional.

Arquivos que começam com "." são arquivos ocultos. 

Um dos exemplos de dotfile é o arquivo .gitignore