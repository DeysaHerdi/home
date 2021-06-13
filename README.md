# 1) Comando 'npx create-react-app nomeDoRepositorio'
# 2) Adicionar no package.json
```
"homepage": "https://deysaherdi.github.io/home/",
  "devDependencies": {
    "gh-pages": "^1.1.0"
  },
  "scripts": {
    "start": "react-scripts start",
    "build": "react-scripts build",
    "test": "react-scripts test",
    "eject": "react-scripts eject",
    "predeploy":"npm run build",
    "deploy":"gh-pages -d build",
    "abrir-pagina":"npm run start",
    "atualizar-site":"npm run predeploy && npm run deploy"
  },
  ```
