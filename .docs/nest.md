# nets

node -v

npm -v

npx -v

npx @nestjs/cli@latest new backend --package-manager npm --skip-install

cd backend

rm -rf .git

npm install
npm run start:dev

git add .
git commit -m "chore(backend): inicializa backend NestJS"
