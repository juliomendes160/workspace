# git

```sh
git -v, --version

git -h, --help

git init
git clone <repo> [<dir>]

git submodule add [-b <branch>] [-f | --force] [--name <name>] <repository> [<path>]


git clone -b blogpessoal-react https://github.com/juliomendes160/generetion

git commit --allow-empty -m "chore: initial commit"
git clone --branch <branch> <repo>  [<dir>]
git subtree add --prefix=<folder-name> <branch-url> <branch-name> [--squash]
git submodule add --force -b <branch-name> <url-repository> [<folder-name>]
git add .gitmodules <submodule-folder>

git clone -b https://github.com/juliomendes160/generetion-portfolio.git portfolio
cd portfolio
git remote remove origin
git remote add origin https://github.com/juliomendes160/generetion
git push --force -u origin main:portfolio

cd generetion
git remote add portfolio https://github.com/juliomendes160/generetion-portfolio.git
git fetch portfolio
git subtree add --prefix=portfolio portfolio main
git push -u origin main

git fetch https://github.com/juliomendes160/generetion-portfolio.git main
git branch portfolio FETCH_HEAD

git fetch https://github.com/juliomendes160/generetion-portfolio.git main
git checkout -b portfolio FETCH_HEAD

git fetch https://github.com/juliomendes160/generetion-portfolio.git main
git rebase FETCH_HEAD

git fetch https://github.com/juliomendes160/generetion-portfolio.git main
git cherry-pick $(git rev-list --reverse FETCH_HEAD)
git commit --allow-empty
```
