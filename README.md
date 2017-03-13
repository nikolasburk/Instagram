# Instagram

This repository contains a GraphQL schema that can be used to build an application similar to Instagram.

You can use it with [`graphql-up`](https://graph.cool/graphql-up/), a tool that let's you quickly get started with a GraphQL API. You can install it via [npm](https://www.npmjs.com/package/graphql-up).

```
npm install -g graphql-up # install graphql-up, if you haven't already
```

Then it's as simple as calling the tool from the command line and passing in the schema file:

```
git clone https://github.com/nikolasburk/Instagram.git
cd Instagram
graphql-up instagram.schema
```

Or if you don't want to clone the repository:

```
graphql-up https://github.com/nikolasburk/Instagram/blob/master/instagram.schema
```

