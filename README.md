# `@wfly/tsconfig`

**English** | [中文](./README.zh_CN.md)

TSConfigs for Vue projects to extend.

Requires TypeScript >= 4.5.

## Install:

```sh
npm add -D @wfly/tsconfig
# or
pnpm add -D @wfly/tsconfig
```

Add one of the available configurations to your `tsconfig.json`:

The base configuration (runtime-agnostic):

```json
"extends": "@wfly/tsconfig/tsconfig.json"
```

Configuration for Browser environment:

```json
"extends": "@wfly/tsconfig/tsconfig.web.json"
```

Configuration for Node environment:

```json
"extends": "@wfly/tsconfig/tsconfig.node.json"
```
