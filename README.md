# `@kdujs/tsconfig`

TSConfigs for Kdu projects to extend.

Requires TypeScript >= 4.5.

Install:

```sh
npm add -D @kdujs/tsconfig
```

Add one of the available configurations to your `tsconfig.json`:

The base configuration (runtime-agnostic):

```json
"extends": "@kdujs/tsconfig/tsconfig.json"
```

Configuration for Browser environment:

```json
"extends": "@kdujs/tsconfig/tsconfig.web.json"
```

Configuration for Node environment:

```json
"extends": "@kdujs/tsconfig/tsconfig.node.json"
```
