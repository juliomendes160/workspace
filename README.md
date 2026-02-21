# code

https://code.visualstudio.com/

```
code --help
code --version
code --install-extension
```

# git

```
git --help
git --version

git init
git commit --allow-empty -m "chore: initial commit"
git clone --branch <branch> <repo>  [<dir>]
git subtree add --prefix=<folder-name> <branch-url> <branch-name> [--squash]
git submodule add --force -b <branch-name> <branch-url> [<folder-name>]
git add .gitmodules <submodule-folder>

git clone https://github.com/juliomendes160/generetion-portfolio.git portfolio
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

# mysql

```
mysql --help
mysql --version

mysql --user=root --password=root --host=localhost --port=3306

help;

create database <db_database>;
drop database <db_database>;
use <db_database>;
select database();
system cd;
exit;
```

# node

https://nodejs.org/pt-br

https://nodejs.org/dist/v20.11.0/node-v20.11.0-win-x64.zip
https://nodejs.org/dist/v22.18.0/node-v22.18.0-win-x64.zip

```
node --help
node --version

npm --help
npm --version

npx --help
npx --version
```

# nest

https://nodejs.org/pt-br
https://nodejs.org/dist/v20.11.0/node-v20.11.0-win-x64.zip

https://nestjs.com/

```
node --version

npm --version

npx --version

npx @nestjs/cli@10.3.2 new <name> --package-manager npm --skip-install

cd <name>

npm install
npm run start:dev
npm run test:e2e
npm run test:e2e <nome_da_classe_teste>
npm run format

rm -rf .git

npx nest --version
npx prettier --write .

npm install --save class-validator class-transformer
npm install --save @nestjs/typeorm typeorm mysql2

npm install --save bcrypt
npm install --save-dev @types/bcrypt

npm install --save @nestjs/passport passport passport-local
npm install --save-dev @types/passport-local

npm install --save @nestjs/jwt passport-jwt
npm install --save-dev @types/passport-jwt

npm install --save-dev supertest
npm install sqlite3

npm install @nestjs/swagger@7.4.2 swagger-ui-express

npx nest generate module postagem 
npx nest generate class postagem --no-spec
npx nest generate service postagem --no-spec
npx nest generate controller postagem --no-spec
```

# react

https://nodejs.org/pt-br

https://nodejs.org/dist/v22.18.0/node-v22.18.0-win-x64.zip

```sh
node --version

npm --version

npx --version

npm create vite@8.1.0 blogpessoal -- --template react-ts --no-rolldown --no-interactive
npx create-vite@8.1.0 blogpessoal -- --template react-ts --no-rolldown --no-interactive

cd blogpessoal
npm install
npm run dev

npm install tailwindcss @tailwindcss/vite
npm install react-router-dom
```