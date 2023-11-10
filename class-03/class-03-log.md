Comandos para ver git log
```bash
git log --pretty=oneline
```

```bash
git log --name-status
```

Configurar um .gitignore global para todos os arquivos
1. Criar um arquivo gitignore: o ~/ aponta para a pasta do usuário atual (C:\Users\MeuUsuario no Windows ou \home\meu_usuario no Linux)
```bash
vim ~/.gitignore
```
1. Para adicionar a configuração do gitignore global, basta executar o seguinte comando:

```bash
git config --global core.excludesfile ~/.gitignore
```

```bash
git grep "termo que estou procurando"
```

O comando git checkout é um coringa do git.

1. Para ver como estava o código em um commit m
```bash
git checkout commit_hash
```

1. Para voltar para o último commit
```bash
git switch -
```