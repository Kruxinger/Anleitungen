created: 28.11.2022 | updated: 28.11.2022
## Table of Content
- [Neues React Projet erstellen](#neues-react-projet-erstellen)
- [React App starten](#react-app-starten)
- [Gitignore file für react erstellen](#gitignore-file-für-react-erstellen)
- [Dependencies installieren](#dependencies-installieren)


# Neues React Projet erstellen
````
npx create-react-app myApp
````
# React App starten
````
cd <pathToReactRootFolder>
npm start
````
pathToReactRootFolder: Da wo "node_modules", "src" und co liegen
# Gitignore file für react erstellen
````
npx react-gitignore
````
Im .gitignore sollte in etwa folgendes stehen:
````
# dependencies
/node_modules
/.pnp
.pnp.js

# testing
/coverage

# production
/build

# misc
.DS_Store
.env.local
.env.development.local
.env.test.local
.env.production.local

npm-debug.log*
yarn-debug.log*
yarn-error.log*
````
# Dependencies installieren
Wenn du das Repo pullst und die Dependencies nachinstallieren möchtest, nutze:
````
npm install
````
