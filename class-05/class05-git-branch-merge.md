Para adicionar um arquivo que está sendo ignorado pelo Git:

```bash
git add arquivo_ignorado.txt -f
```

Para editar arquivos depois de ter commitado, mas antes de fazer o push.

```bash
git commit --amend -m "mensagem"
```

Para apagar uma branch:

```bash
git branch -D
```

Para ver a diferença entre dois commits
```bash
git diff main..develop
```

O problema de commits diferentes em um mesmo arquivo que geram conflito é a alteração em linhas próximas

Para adicionar os arquivos e commitar em um comando só:
```bash
git commit -am "Commit message"
```