# 前言

### 项目简介

**FS-Context**是 ~~一个名叫**FallingShrimp**的Furry觉得做拓展简直就是种折磨于是闲着没事研究的~~ 一个易用的**TypeScript**上下文，用于开发通用于`TurboWarp/GandiIDE`等ScratchMod的积木拓展。提供了一些拓展开发中较常用的工具/脚手架。

本项目仅仅由于个人兴趣而完成，开发目的仅为探索，也许代码也有优化空间，欢迎各位大佬提出建议。

### 项目初衷

不管在什么平台下，开发拓展都非常的折磨，缺少类型提示/自动补全/代码不易读，以及不同平台对`runtime`和`vm`的沙盒机制都有严重差异。通用拓展需要编写非常多的并不必要的冗余代码。

因此，本项目旨在提供一些`TS类型提示`与`工具集`，同时将不同平台加载拓展/获取vm等频繁且常用的操作封装，开发者不需要重复制造轮子，可以专注于**积木逻辑**的开发。

### 项目结构

```plaintext
root
- node_modules/
| - ...
- src/
| - extension.ts
| - fs-context/
||| - ...
- package.json
- tsconfig.json
```
**文件/夹 解释**
- `extension.ts`：拓展入口文件，定义了l10n、积木、菜单等内容
- `fs-context`：项目核心
- `package.json`：项目配置文件
- `tsconfig.json`：TypeScript配置文件

### 快速上手

::: details 只需三步
1. 安装依赖
```bash
npm install
```

2. 启动开发服务器
```bash
npm run dev
```

3. 编译生产环境代码
```bash
npm run dist
```
:::
对于新的拓展API文档，访问[概念和API](./quickstart.md)

### 贡献

[Github](https://github.com/Rundll86/fs-context)  
欢迎提交`Issue`或`Pull Request`，欢迎`Star`。

#### 项目贡献者

<Collaborator
name="FallingShrimp"
avatar="https://avatars.githubusercontent.com/u/108387605"
url="https://github.com/Rundll86"></Collaborator>
<Collaborator
name="FurryR/熊谷 凌"
avatar="https://avatars.githubusercontent.com/u/55276797"
url="https://github.com/FurryR"></Collaborator>
<Collaborator
name="Cyberexplorer"
avatar="https://avatars.githubusercontent.com/u/177754635"
url="https://github.com/LanwyWriteXU"></Collaborator>