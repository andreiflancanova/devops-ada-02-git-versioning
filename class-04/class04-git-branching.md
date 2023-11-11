>## Módulo 02 - Aula 02 - Git Diff-Add-Commit

Para criar uma branch, podemos utilizar:

```bash
git branch nome_branch
```

```bash
git checkout -b "nome_branch"
```

Um site para ver a dinâmica de commits e branchs é o [Visualizing Git](https://git-school.github.io/visualizing-git/#free-remote).

Para renomear uma branch, você pode usar:

```bash
git branch -m novo_nome
```

 O git checkout --orphan serve pra ser possível que commits tenham ancestrais diferentes. Isso serve para mapear vários projetos diferentes em diferentes branches em um único repositório.

```bash
git checkout --orphan
```

Para mergear o conteúdo de uma branch na sua branch main, estando na branch main, execute o comando:
```bash
git merge minha_branch
```

```bash
git checkout -b develop
```

```bash
git checkout -b tmp
```

Para reverter as alterações sem 
```bash
git checkout nome_arquivo.txt
```

Se um merge der conflito, você pode cancelar o merge com 

```bash
git merge --abort
```

