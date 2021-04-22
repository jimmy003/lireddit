npm init -y
npm i -D @types/node typescript
npm i -D ts-node
npx tsconfig.json
npm run watch
npm i -D nodemon
npm run dev

# mikro-orm

npm i @mikro-orm/cli @mikro-orm/core @mikro-orm/migrations @mikro-orm/postgresql pg

# references

https://github.com/mikro-orm/mikro-orm/issues/866

https://mikro-orm.io/docs/installation/#setting-up-the-commandline-tool

https://mikro-orm.io/docs/migrations/#using-via-cli

npx mikro-orm migration:create

## setup of Apollo Server Express Setup

npm i express
