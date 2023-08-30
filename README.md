
# DIO | Resumos Git e GitHub

Repositório para armazenar resumos sobre Git e GitHub do curso "Versionamento de Código com Git e GitHub" da 
[Digital Innovation One](https://www.dio.me/).

## 📚 Documentação
- [Documentação Git](https://git-scm.com/doc)
- [Documentação Gitub](https://docs.github.com/)

## 💻 Resumos das Aulas

### Pull dos arquivos para o repositório
```
$ git init 
$ git add .
$ git status
$ git commit -m ""
$ git push
$ git pull
```

### Desfazer um git init
Caso tenha feito um git init em um diretório errado
```
$ rm -rf .git
```
### Restaurar um arquivo local
Caso tenha modificado algum arquivo e queira desfazer essa alteração
```
$ git restore [nome_do_arquivo]
```

### Histórico de commits
```
$ git log
```

### Editar nome do commit
```
$ git commit -amend -m "nova mensagem de commit"
```

### Criar, Visualizar e Deletar uma branch
Criar uma ramificação
```
$ git checkout -b nome_branch
```
Visualizar as ramificações
```
$ git branch
```

Deletar uma ramificação
```
$ git checkout -d nome_branch
```

### Clonar somente uma branch específica
```
$ git clone https://... --branch nome-branch --single-branch
```

### o git irá sempre iniciar o repositório com o branch main como padrão.
```
$ git config --global init.defaultBranch main
```
