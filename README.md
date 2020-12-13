# Svelte setup

## Steps

1. get template

```
npx degit sveltejs/template project
npm install
```

2. Prepared for TypeScript use

```
cd ./scripts
node setupTypeScript.js
npm install
```

3. Adding sass support

```
npm install svelte-preprocess node-sass
```

## Run

```
npm run dev
```

## VS Code specific

- Fix the language server by adding to the settings.json

```
"svelte.language-server.runtime": "/home/redder/.nvm/versions/node/v15.3.0/bin/node"
```
