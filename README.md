<br />

<div align="center">
  <h1>Prisma Examples</h1>
  <p><h3 align="center">Ready-to-run Prisma example projects 🚀</h3></p>
  <a href="https://www.prisma.io/">Website</a>
  <span>&nbsp;&nbsp;•&nbsp;&nbsp;</span>
  <a href="https://www.prisma.io/docs/">Docs</a>
  <span>&nbsp;&nbsp;•&nbsp;&nbsp;</span>
  <a href="https://www.prisma.io/blog">Blog</a>
  <span>&nbsp;&nbsp;•&nbsp;&nbsp;</span>
  <a href="https://slack.prisma.io/">Slack</a>
  <span>&nbsp;&nbsp;•&nbsp;&nbsp;</span>
  <a href="https://twitter.com/prisma">Twitter</a>
  <span>&nbsp;&nbsp;•&nbsp;&nbsp;</span>
  <a href="https://www.youtube.com/watch?v=0RhtQgIs-TE&list=PLn2e1F9Rfr6k9PnR_figWOcSHgc_erDr5&index=1">Demo videos</a>
</div>

<hr>

<div align="center">	

[![test](https://github.com/prisma/prisma-examples/workflows/test/badge.svg?branch=latest)](https://github.com/prisma/prisma-examples/actions?query=workflow%3Atest+branch%3Alatest)
[![keep-prisma-dependencies-updated](https://github.com/prisma/prisma-examples/workflows/keep-prisma-dependencies-updated/badge.svg)](https://github.com/prisma/prisma-examples/actions?query=workflow%3Akeep-prisma-dependencies-updated)
[![keep-dev-branches-in-sync-with-latest](https://github.com/prisma/prisma-examples/workflows/keep-dev-branches-in-sync-with-latest/badge.svg)](https://github.com/prisma/prisma-examples/actions?query=workflow%3Akeep-dev-branches-in-sync-with-latest)

[View full CI status](#ci-status)

</div>

<hr>


This repository contains a number of ready-to-run example projects demonstrating various use cases of Prisma. Pick an example and follow the instructions in the corresponding README.

You can also find links to [real-world and production ready examples](#real-world--production-ready-example-projects-with-prisma) further below in this README.

Are you missing an example? Please feel free to [open an issue](https://github.com/prisma/prisma-examples/issues/new) (read the [contribution guidelines](./CONTRIBUTING.md) for more info).

<!-- Please keep the absolute URLs so it's easier to copy&paste to prisma/prisma/README.md  -->

## TypeScript

### Fullstack

| Demo                                                                                                                          | Description                                                                                                                                                                                          |
| :---------------------------------------------------------------------------------------------------------------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [`rest-nextjs-api-routes`](https://github.com/prisma/prisma-examples/tree/latest/typescript/rest-nextjs-api-routes)           | [Next.js](https://nextjs.org/) app with a REST API (using [Next.js API routes](https://nextjs.org/docs/api-routes/introduction))                                                                     |
| [`rest-nextjs-api-routes-auth`](https://github.com/prisma/prisma-examples/tree/latest/typescript/rest-nextjs-api-routes-auth) | [Next.js](https://nextjs.org/) app with a REST API (using [Next.js API routes](https://nextjs.org/docs/api-routes/introduction)) and authentication (using [NextAuth.js](https://next-auth.js.org/)) |
| [`rest-nextjs-express`](https://github.com/prisma/prisma-examples/tree/latest/typescript/rest-nextjs-express)                 | [Next.js](https://nextjs.org/) app with a REST API (using [Express](https://expressjs.com/))                                                                                                         |
| [`graphql-nextjs`](https://github.com/prisma/prisma-examples/tree/latest/typescript/graphql-nextjs)                           | [Next.js](https://nextjs.org/) app with a GraphQL API (using [Apollo Server](https://github.com/apollographql/apollo-server) and [Nexus Schema](https://github.com/graphql-nexus/schema))            |

### Backend only

| Demo                                                                                                                      | Description                                                                                                                                                                          |
| :------------------------------------------------------------------------------------------------------------------------ | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [`graphql-apollo-server`](https://github.com/prisma/prisma-examples/tree/latest/typescript/graphql-apollo-server)         | GraphQL server based on [`apollo-server`](https://www.apollographql.com/docs/apollo-server/) and [Nexus Schema](https://github.com/graphql-nexus/schema)                             |
| [`graphql-auth`](https://github.com/prisma/prisma-examples/tree/latest/typescript/graphql-auth)                           | GraphQL server with email-password authentication & permissions                                                                                                                      |
| [`graphql-sdl-first`](https://github.com/prisma/prisma-examples/tree/latest/typescript/graphql-sdl-first)                 | GraphQL server based on the SDL-first approach of [`graphql-tools`](https://www.apollographql.com/docs/graphql-tools/)                                                               |
| [`graphql-subscriptions`](https://github.com/prisma/prisma-examples/tree/latest/typescript/subscriptions-pubsub)          | GraphQL server with realtime subscriptions based on [`apollo-server`](https://www.apollographql.com/docs/apollo-server/) and [Nexus Schema](https://github.com/graphql-nexus/schema) |
| [`graphql-typegraphql`](https://github.com/prisma/prisma-examples/tree/latest/typescript/graphql-typegraphql)             | GraphQL server based on [`graphql-yoga`](https://github.com/prisma-labs/graphql-yoga) and [TypeGraphQL](https://github.com/MichalLytek/type-graphql)                                 |
| [`graphql-express`](https://github.com/prisma/prisma-examples/tree/latest/typescript/graphql-express)                     | GraphQL server based on [Express](https://expressjs.com/) and [Nexus Schema](https://github.com/graphql-nexus/schema)                                                                 |
| [`graphql-express-sdl-first`](https://github.com/prisma/prisma-examples/tree/latest/typescript/graphql-express-sdl-first) | GraphQL server based on [Express](https://expressjs.com/) and the SDL-first approach of [`graphql-tools`](https://www.apollographql.com/docs/graphql-tools/)                             |
| [`graphql`](https://github.com/prisma/prisma-examples/tree/latest/typescript/graphql)                                     | GraphQL server based on [`graphql-yoga`](https://github.com/prisma-labs/graphql-yoga) and [Nexus Schema](https://github.com/graphql-nexus/schema)                                    |
| [`grpc`](https://github.com/prisma/prisma-examples/tree/latest/typescript/grpc)                                           | gRPC API including runnable client scripts for testing                                                                                                                               |
| [`postgis-express`](https://github.com/prisma/prisma-examples/tree/latest/typescript/postgis-express)                     | Demo of spatial queries using [Postgis](http://postgis.net/) and [Express](https://expressjs.com/)                                                                                   |
| [`rest-express`](https://github.com/prisma/prisma-examples/tree/latest/typescript/rest-express)                           | REST API with [Express](https://expressjs.com/)                                                                                                                                      |
| [`script`](https://github.com/prisma/prisma-examples/tree/latest/typescript/script)                                       | Usage of Prisma Client JS in a TypeScript script                                                                                                                                     |
| [`testing-express`](https://github.com/prisma/prisma-examples/tree/latest/typescript/testing-express)                     | Demo of integration tests with [Jest](https://jestjs.io/), [Supertest](https://github.com/visionmedia/supertest) and [Express](https://expressjs.com/)                               |

## JavaScript (Node.js)

### Fullstack

| Demo                                                                                          | Description                                                                                                                      |
| :-------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------- |
| [`rest-nextjs`](https://github.com/prisma/prisma-examples/tree/latest/javascript/rest-nextjs) | [Next.js](https://nextjs.org/) app with a REST API (using [Next.js API routes](https://nextjs.org/docs/api-routes/introduction)) |

### Backend only

| Demo                                                                                                              | Description                                                                                                            |
| :---------------------------------------------------------------------------------------------------------------- | :--------------------------------------------------------------------------------------------------------------------- |
| [`graphql-apollo-server`](https://github.com/prisma/prisma-examples/tree/latest/javascript/graphql-apollo-server) | GraphQL server based on [`apollo-server`](https://www.apollographql.com/docs/apollo-server/)                           |
| [`graphql-auth`](https://github.com/prisma/prisma-examples/tree/latest/javascript/graphql-auth)                   | GraphQL server with email-password authentication & permissions                                                        |
| [`graphql-sdl-first`](https://github.com/prisma/prisma-examples/tree/latest/javascript/graphql-sdl-first)         | GraphQL server based on the SDL-first approach of [`graphql-tools`](https://www.apollographql.com/docs/graphql-tools/) |
| [`graphql`](https://github.com/prisma/prisma-examples/tree/latest/javascript/graphql)                             | GraphQL server based on [`graphql-yoga`](https://github.com/prisma-labs/graphql-yoga)                                  |
| [`grpc`](https://github.com/prisma/prisma-examples/tree/latest/javascript/grpc)                                   | gRPC API including runnable client scripts for testing                                                                 |
| [`rest-express`](https://github.com/prisma/prisma-examples/tree/latest/javascript/rest-express)                   | REST API with [Express](https://expressjs.com/)                                                                        |
| [`rest-fastify`](https://github.com/prisma/prisma-examples/tree/latest/javascript/rest-fastify)                   | REST API with [Fastify](https://www.fastify.io/)                                                                       |
| [`script`](https://github.com/prisma/prisma-examples/tree/latest/javascript/script)                               | Usage of Prisma Client JS in a Node.js script                                                                          |

## Experimental

The [`experimental`](./experimental) directory contains the same examples as the `javascript` and `typescript` directories. The main difference is that it uses [Prisma Migrate](https://www.prisma.io/docs/reference/tools-and-interfaces/prisma-migrate) to perform database migrations which are currently an experimental feature.

## Deployment platforms

The projects in the [`deployment-platforms`](./deployment-platforms) directory show what "Prisma Client"-based deployment setups look like for various deployment providers. Learn more about [deployment](https://www.prisma.io/docs/reference/tools-and-interfaces/prisma-client/deployment) in the Prisma documentation.

## Real-world & production-ready example projects with Prisma

- [Backend for a real world grading application](https://github.com/2color/real-world-grading-app) (incl video and written tutorials)
- [Tottem – Fullstack app for "social library management"](https://github.com/poulainv/tottem) (based on Next.js)

<hr>

## About this repository

The `latest` branch of this repository contains the examples with the latest stable version of Prisma CLI and Prisma Client (`@latest` on npm). These dependencies are kept up to date with a GitHub Action workflow, which updates them every time a new version of Prisma is released.

There are also the automated branches `dev` and `patch-dev`, which mirror the code from `latest` (synced via a GitHub Action workflow), but they use the respective development channels of Prisma CLI and Prisma Client from npm instead (`@dev` and `@patch-dev`, also updated via a GitHub Action workflow). Thanks to the test coverage of all projects, this can point us to incompatibilities early.

## Security

If you have a security issue to report, please contact us at [security@prisma.io](mailto:security@prisma.io?subject=[GitHub]%20Prisma%202%20Security%20Report%20Examples)

## CI status

| CI Status | Branch |
|-|-|
| [![test latest](https://github.com/prisma/prisma-examples/workflows/test/badge.svg?branch=latest)](https://github.com/prisma/prisma-examples/actions?query=workflow%3Atest+branch%3Alatest) | `latest` |
| [![test dev](https://github.com/prisma/prisma-examples/workflows/test/badge.svg?branch=dev)](https://github.com/prisma/prisma-examples/actions?query=workflow%3Atest+branch%3Adev+-branch%3Apatch-dev) | `dev` |
| [![test patch-dev](https://github.com/prisma/prisma-examples/workflows/test/badge.svg?branch=patch-dev)](https://github.com/prisma/prisma-examples/actions?query=workflow%3Atest+branch%3Apatch-dev) | `patch-dev` |

| CI Status |
|-|
| [![keep-prisma-dependencies-updated](https://github.com/prisma/prisma-examples/workflows/keep-prisma-dependencies-updated/badge.svg)](https://github.com/prisma/prisma-examples/actions?query=workflow%3Akeep-prisma-dependencies-updated) |
| [![keep-dev-branches-in-sync-with-latest](https://github.com/prisma/prisma-examples/workflows/keep-dev-branches-in-sync-with-latest/badge.svg)](https://github.com/prisma/prisma-examples/actions?query=workflow%3Akeep-dev-branches-in-sync-with-latest) |


