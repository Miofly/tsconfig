# `@vri/tsconfig`

**English** | [中文](./README.zh_CN.md)

TSConfigs for Vue projects to extend.

Requires TypeScript >= 4.5.

## Install:

```sh
npm add -D @vri/tsconfig
# or
pnpm add -D @vri/tsconfig
```

Add one of the available configurations to your `tsconfig.json`:

The base configuration (runtime-agnostic):

```json
"extends": "@vri/tsconfig/tsconfig.json"
```

Configuration for Browser environment:

```json
"extends": "@vri/tsconfig/tsconfig.web.json"
```

Configuration for Node environment:

```json
"extends": "@vri/tsconfig/tsconfig.node.json"
```
