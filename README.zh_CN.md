# `@wfly/tsconfig`

**中文** | [English](./README.md)

`Vue` 项目的 `tsconfig` 基础配置。

要求 `TypeScript` 版本 `>= 4.5`

## 安装

```sh
npm add -D @wfly/tsconfig
# or
pnpm add -D @wfly/tsconfig
```

基本配置

```json
"extends": "@wfly/tsconfig/tsconfig.json"
```

浏览器环境的配置

```json
"extends": "@wfly/tsconfig/tsconfig.web.json"
```

`Node` 环境的配置

```json
"extends": "@wfly/tsconfig/tsconfig.node.json"
```
