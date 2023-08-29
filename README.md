
# DIO | Resumos Git e GitHub

Repositório para armazenar resumos sobre Git e GitHub do curso "Versionamento de Código com Git e GitHub" da 
[Digital Innovation One](https://www.dio.me/).

## 📚 Documentação
- [Documentação Git](https://git-scm.com/doc)
- [Documentação Gitub](https://docs.github.com/)

## 💻 Resumos das Aulas

| Aulas | Resumos |
| -----| ------- |
| Anotações sobre Git e GitHub | [Notion](https://bootcamp-java-isa.notion.site/GIT-2d8f9571bb674c838e413c677502a584?pvs=4) |

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

