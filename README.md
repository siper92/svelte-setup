# Svelte setup

## steps

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

3. Fix the language server by adding to the settings.json

```
"svelte.language-server.runtime": "/home/redder/.nvm/versions/node/v15.3.0/bin/node"
```

## Run

```
npm run dev
```
