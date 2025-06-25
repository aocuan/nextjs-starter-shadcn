# Next.js 15 启动模板（shadcn）

![MIT 许可证](https://img.shields.io/badge/license-MIT-blue) [![TypeScript](https://badgen.net/badge/icon/typescript?icon=typescript&label)](https://typescriptlang.org) ![ESLint](https://img.shields.io/badge/code%20style-eslint-brightgreen)

*这是 Next.js 15 启动模板的 Tailwind 版本，你也可以关注其他模板：*

- [**Next.js 15 Starter Core**](https://github.com/SiddharthaMaity/nextjs-15-starter-core)
- [**Next.js 15 Starter with Tailwind CSS**](https://github.com/SiddharthaMaity/nextjs-15-starter-tailwind)

欢迎使用 **Next.js 15 启动模板**！本模板基于 Next.js 15、React 19、TypeScript 5、Tailwind CSS 3、Shadcn UI 构建，集成了多种强大工具和配置，助你快速搭建项目并提升 VS Code 下的开发效率。

## 🚀 包含内容

- **Next.js 15**
- **React 19**
- **TypeScript 5**
- **ESLint 9**
- **Prettier 3**
- **Tailwind CSS 4**
- **Shadcn UI**
- **App 目录结构**
- **系统、明亮与暗黑模式**
- **Next.js Bundle Analyzer**
- **Dockerfile**（Node.js 22.16.0，Alpine）
- **Dockerfile.bun**（Bun 1.2.17，Alpine）

### 🛠️ ESLint 插件

- [**@eslint/js**](https://www.npmjs.com/package/@eslint/js)
- [**typescript-eslint**](https://github.com/typescript-eslint/typescript-eslint)
- [**eslint-plugin-react**](https://github.com/jsx-eslint/eslint-plugin-react)
- [**@next/eslint-plugin-next**](https://github.com/vercel/next.js)
- [**eslint-config-prettier**](eslint-config-prettier)
- [**eslint-plugin-tailwindcss**](https://github.com/francoismassart/eslint-plugin-tailwindcss)
- [**eslint-plugin-import**](https://github.com/import-js/eslint-plugin-import)
- [**eslint-plugin-promise**](https://github.com/eslint-community/eslint-plugin-promise)

### ✨ Prettier 插件

- [**@trivago/prettier-plugin-sort-imports**](https://github.com/trivago/prettier-plugin-sort-imports)
- [**prettier-plugin-tailwindcss**](https://github.com/tailwindlabs/prettier-plugin-tailwindcss)

### 💻 推荐 VS Code 扩展

为提升开发体验，建议安装以下 VS Code 扩展。这些扩展已在工作区配置文件中推荐，可以通过 VS Code 的扩展面板直接安装。

> 💡 **提示**：这些推荐扩展基于团队开发经验精选，可根据个人需求自由增删。详情请见 [VS Code 工作区推荐扩展文档](https://go.microsoft.com/fwlink/?LinkId=827846)

- [**Next.js Snippets**](https://marketplace.visualstudio.com/items?itemName=PulkitGangwar.nextjs-snippets) - Next.js 代码片段
- [**Auto Close Tag**](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag) - 自动闭合标签
- [**Better Comments**](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments) - 注释增强
- [**DotENV**](https://marketplace.visualstudio.com/items?itemName=mikestead.dotenv) - 环境变量语法高亮
- [**EditorConfig for VS Code**](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig) - 编辑器配置
- [**ESLint**](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) - 代码规范检查
- [**formate: CSS/LESS/SCSS formatter**](https://marketplace.visualstudio.com/items?itemName=MikeBovenlander.formate) - 样式文件格式化
- [**Git History**](https://marketplace.visualstudio.com/items?itemName=donjayamanne.githistory) - Git 历史查看
- [**Import Cost**](https://marketplace.visualstudio.com/items?itemName=wix.vscode-import-cost) - 依赖包体积显示
- [**JavaScript Booster**](https://marketplace.visualstudio.com/items?itemName=sburg.vscode-javascript-booster) - JavaScript 代码增强
- [**npm Intellisense**](https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense) - npm 包智能提示
- [**Prettier - Code formatter**](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) - 代码格式化
- [**Turbo Console Log**](https://marketplace.visualstudio.com/items?itemName=ChakrounAnas.turbo-console-log) - 快速生成日志
- [**Package Json Upgrade**](https://marketplace.visualstudio.com/items?itemName=codeandstuff.package-json-upgrade) - 依赖包升级助手
- [**Visual Studio Code Commitizen Support**](https://marketplace.visualstudio.com/items?itemName=KnisterPeter.vscode-commitizen) - 提交规范支持
- [**Markdown All in One**](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one) - Markdown 全能工具
- [**Tailwind CSS IntelliSense**](https://marketplace.visualstudio.com/items?itemName=bradlc.vscode-tailwindcss) - Tailwind CSS 智能提示
- [**Tailwind Docs**](https://marketplace.visualstudio.com/items?itemName=austenc.tailwind-docs) - Tailwind 文档查看

## 🏁 快速开始

### 前置条件

- **Bun**：版本 1.2.17 及以上 或
- **Node.js**：版本 20.18.0 及以上
- **Docker**：用于容器化部署（可选但推荐）

### 🐳 Docker 部署

如需使用 Docker，请确保本地已安装 Docker。然后构建并运行容器：

```bash
docker build . -t nextjs-starter-shadcn
# 或使用 Bun
docker build . -t nextjs-starter-shadcn -f Dockerfile.bun

docker run -p 3000:3000 nextjs-starter-shadcn
```

### 许可证

本项目基于 MIT 许可证开源。详情请见 [LICENSE](LICENSE) 文件。

## 感谢

> 本项目基于 [Next.js 15 启动模板（shadcn）](https://github.com/SiddharthaMaity/nextjs-15-starter-shadcn) 修改而来，感谢原作者。
