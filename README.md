# lp-subgraph

A subgraph that indexes The LP events and calls.

## Quickstart

```sh
yarn
```

## The LP Subgraph

This repo contains the templates for compiling and deploying a graphql schema to thegraph.

### Authenticate

To authenticate for thegraph deployment use the `Access Token` from thegraph dashboard:

```sh
yarn run graph auth https://api.thegraph.com/deploy/ $ACCESS_TOKEN
```

### Generate types to use with Typescript

```sh
yarn codegen
```

### Build the subgraph

```sh
yarn build
```

### Deploy to thegraph (must be authenticated)

```sh
# Official Subgraph
yarn deploy
```

## Running a local deployment

Make sure you have Docker installed.
Run your local graph node by running:

```sh
yarn graph-node
```

Create and deploy to local graph node:

```sh
yarn create-local
```

```sh
yarn deploy-local
```
