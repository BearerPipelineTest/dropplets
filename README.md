# fire-nuxt-vince

> My stellar Nuxt.js project

## Build Setup

``` bash
# install dependencies
$ yarn install

# serve with hot reload at localhost:3000
$ yarn dev

# serve with firebase functions
$ yarn build:firebase
$ yarn start:firebase

# deploy project on Firebase Hosting
$ yarn build:firebase
$ yarn deploy

```

For detailed explanation on how things work, check out [Nuxt.js docs](https://nuxtjs.org).

## Trucs important

- `~` or `@` for [srcDir](https://nuxtjs.org/api/configuration-srcdir)
- `~~` or `@@` for [rootDir](https://nuxtjs.org/api/configuration-rootdir)

------

## Création d'un nouveau projet

> Cette section permet d'aider à la création de nouveaux projets dans l'avenir.

### Installation de Firebase

Sur un nouveau projet, si on installe Firebase avec `yarn` via `yarn add firebase` et qu'on tente de lancer le projet, on va se rendre compte qu'il ne compile plus. (Pourtant ça marche correctement avec `npm`)

Pour installer firebase correctement voici la méthode :

``` bash
# install firebase
$ yarn add firebase

# install missing dependencies
$ yarn add -D core-js@2 @babel/runtime-corejs2
```

Et là, ça devrait compiler normalement.

------

## Liens important

> Pour éviter de galérer, voici la liste des liens qui sont importants pour le projet.

### Librarie Nuxt Fire 🔥

- [Github](https://github.com/lupas/nuxt-fire)
- [Documentation](https://nuxtfire.netlify.com/)

### Deploy Nuxt on Firebase 🚀

- [Tuto](https://dev.to/kiritchoukc/deploy-nuxt-on-firebase-4ad8)
