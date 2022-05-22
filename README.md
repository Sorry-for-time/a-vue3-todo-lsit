# Hi👋

## About

> 最近刷了 B 站的教程学习了下 vue3, 为了不那么快就把听的东西全部忘记掉了 🤣, 因此写个人人都会写的 todo-list 来稍微打实一下 vue3 的使用基础

## Toolkit

- 如果你想启动这个项目, 那么你需要安装有 nodejs 环境 和 vue-cli 工具, 原因如下
- 这个项目使用了 vite + vue3-ts 的配置, 使其开发更加快速 ⚡ 和愉悦 😊
- 使用了 scss 来简化 css 的编写, 请无视我拙劣的样式编写水平 🤣
- 既然是 vue3, 那肯定使用了一些 vue 的生态系统插件
  - vue-router
  - vuex

## Run && Build

- 你可以通过修改 package.json 里的 scripts 来进行自定义更改, 底下为项目默认运行配置

- 随便通过一个 `shell` 进入项目文件夹内
  ```sh
  cd a-vue3-todo-list
  ```
- 安装必要的依赖
  ```sh
  npm install
  ```
- 启动开发服务器
  ```sh
  npm run dev
  ```
- 打包文件
  ```sh
  npm run build
  # 执行完成后会在项目目录内生成一个 dist 文件夹
  # 你可以通过 nginx, github 静态页等进行部署, 就不多言了
  ```

## LAST

- Enjoy it
