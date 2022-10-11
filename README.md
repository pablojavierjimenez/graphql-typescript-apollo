# graphql-typescript-apollo

this repo is based on this two tutorials:

- [Set up Node.js project with Typescript, ESLint and Prettier](https://blog.tericcabrel.com/set-up-a-nodejs-project-with-typescript-eslint-and-prettier/)
- [Create a GraphQL application with Node.js and Apollo server 3](https://blog.tericcabrel.com/create-a-graphql-application-with-node-js-and-apollo/)

## Steps

1. **Setting environment**
    _you can check node versions here [NodeJS Release List](https://nodejs.org/en/download/releases/)_,
    here we use `Node.js LTS 16.17.1 Gallium 2022-09-23`

    ```bash
    :~$ nvm install 16.17.1
    ```

2. **Installing dependencis**

```bash
    :~$ npm i typescript
    :~$ npm i -D @types/node ts-node nodemon
    ```
3. **Setting typescript config**
    ```bash
    :~$ npx tsconfig.json
    ```
4. **Setting Linters configs**
    ```bash
    :~$ npm i -D eslint eslint-config-prettier eslint-plugin-prettier @typescript-eslint/eslint-plugin @typescript-eslint/parser
    ```
