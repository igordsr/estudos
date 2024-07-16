#DIO | Resumo Git e Github

Repositório para armazenar resumos sobre o Git e Github

## 📚
- [Documentação Git](https://git-scm.com/doc)

- [Documentação Github](https://docs.github.com/pt/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/quickstart-for-writing-on-github)

## 🖥️ Resumos das Aulas

| Aulas | Resumo |
| ------| ------ |
| Gravando Alterações no Réposiótio Local | [Resumos]() |

```
    git init
```

## 🔎 Referências
- [Digital Innovation One]().


## 👨‍💻Comandos
1. Para ver o estado (situção dos projetos) do diretório
```
    git status
```

2. Para adicionar o arquivo na área de preparação
```
    git add README.md
```

3. Para fazer o commit das alterações
```
    git commit -m 'Seu texto de descrição do commit'
```

4. Para ver os logs do commit
```
    git log
```

5. Para desfazer modificações feitas em algum arquivo
```
    git restore nome_do_arquivo.txt
```

6. Para alterar descrição do ultimo commit
```
    git commit --amend -m "Incluindo comandos do git"
```
ou

```
    git commit --amend
```
Esse ultimo comando ele vai abrir o editor para editar o commit, ai só apertar a tecla I em seguida editar o commit, para sair apenas precionsar a tecla "esc" depois ":" e escrever wq e apertar "enter"

7. Removendo intens comitados da area de preparação
```
    git reset --soft hashcomit_qiueyqiuwyeuqywie
```

8. Removendo intens comitados da area de preparação
```
    git reset --soft hashcomit_qiueyqiuwyeuqywie
```

9. Vinculando um repositório local ao repositório no servidor
```
    git remote add origin https://github.com/igordsr/estudos.git
```

10. Criando uma branch
```
    git branch nome_da_branch
```

11. Selecionando um branch
```
    git checkout nome_da_branch
```

12. Baixando as atualizações do diretório remoto
```
    git pull
```

13. Atualizando a branch local com as informações da branch remota
```
    git merge origin/main
```

ou

```
    git merge nome_da_branch origin
```

14. Deletando uma branch
```
    git branch -d nome_da_branch
```

15. Baixando atualizações do diretório remoto mas sem alterar a branch local
```
    git fetch origin main
```
