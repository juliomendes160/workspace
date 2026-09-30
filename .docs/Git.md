# Git

https://git-scm.com/install/windows

```bash
git [-h | --help]

git [-v | --version]
```

```bash 
rm -rf .git

git init

git commit --allow-empty -m "Initial commit"

git add .
git commit -m "" 

git remote add origin "https://github.com/juliomendes160/dio.git"
git branch -M "main"
git push -u origin "main"
```

```bash
git config --global user.name "Juliermes Mendes"
git config --global user.email "juliomendes160@hotmail.com"
```

# rm
rm [OPTION]... [FILE]...
rm --help
rm -rf .git

# clone
git clone [<options>] [--] <repo> [<dir>]
git clone -b <branch> <repo> [<dir>]

```bash
git submodule add [-b <branch>] [-f|--force] [--name <name>] [--reference <repository>] [--] <repository> [<path>]
git add .
git restore --staged .
```

```bash
git subtree add --prefix=<folder-name> <branch-url> <branch-name> [--squash]
```

# remote
git remote -v
git remote remove origin
git remote add origin <repo>
git remote remove dio
git remote add dio <repo>


```bash
git branch -M "Criando-uma-API-REST-Documentada-com-Spring-Web-e-Swagger"
git push -u origin "Criando-uma-API-REST-Documentada-com-Spring-Web-e-Swagger"
```