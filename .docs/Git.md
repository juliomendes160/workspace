# Git

https://git-scm.com/install/windows

```bash
git -h
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

# commit
git commit -h
git commit --allow-empty -m <msg>

# clone
git clone -h

git clone [<options>] [--] <repo> [<dir>]

git add .


```bash
git subtree add --prefix=<folder-name> <branch-url> <branch-name> [--squash]
```

# push
git push -h

git push -f

git push -u origin <branch>

# remote
git remote -v

git remote remove origin

git remote add origin <repo>

git remote remove dio

git remote add dio <repo>

# rm
rm --help
rm [OPTION] [FILE]
rm -rf .git

# submodule
git submodule -h

git submodule [--quiet] add [-b <branch>] [-f|--force] [--name <name>] [--reference <repository>] [--] <repository> [<path>]

git add .

git restore --staged .

```bash
git branch -M "Criando-uma-API-REST-Documentada-com-Spring-Web-e-Swagger"
git push -u origin "Criando-uma-API-REST-Documentada-com-Spring-Web-e-Swagger"
```

# update
git update-ref -d HEAD