# CYarn

> 使用 cnpm 源的 Yarn

Yarn 是一个快速、可靠、安全的 JavaScript 依赖管理工具。

- Yarn 文档：https://yarnpkg.com/ （官方网站支持多语言，但是中文文档还没有）

## 安装 CYarn

```shell
npm install -g cyarn
```

或者使用 cnpm 源：

```shell
npm install -g cyarn --registry=https://registry.npm.taobao.org
```

## 其他修改源的方式

### 配置 yarn config

https://yarnpkg.com/en/docs/cli/config

```shell
yarn config set registry https://registry.npm.taobao.org
```

### 使用 yrm

https://github.com/i5ting/yrm

```shell
npm install -g yrm
yrm use cnpm
```

## 现有技术

CYarn 离不开这些现有技术：

 - [Yarn](https://github.com/yarnpkg/yarn)
 - [cnpm](https://github.com/cnpm/cnpm)
