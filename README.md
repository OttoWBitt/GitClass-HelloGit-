GitClass-HelloGit-
---

Comando específico

```sh
$ git help add
$ git help commit
$ git help <qualquer_comando_git>
```

Começando a usar o Git e GitHub

- Iniciando um repositório:
```sh
$ git init
```

- Como ver o status do seu repositório:
```sh
$ git status
```

- Adicionando arquivos:
```sh
$ git add <arquivo>
```

Adicionar todos os arquivos/diretórios

```sh
$ git add .
```

- Fazendo um commit:
```sh
$ git commit -m "Mensagem explicando"
```

- Mandando para o GitHub:
```sh
$ git push -u origin master
```

- Como voltar atrás:
```sh
$ git pull origin master
```

Adicionar um arquivo que esta listado no .gitignore (geral ou do repositório)

```sh
$ git add -f arquivo_no_gitignore.txt
```
