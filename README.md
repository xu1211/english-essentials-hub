[toc]

# english-essentials-hub

## frontend
- 创建typescript的react项目
```shell
  npx create-react-app 项目名 --template typescript
```
### Folder Structure
执行命令后会创建好默认项目, 重要文件如下

```shell
项目名/
├─ public  # 包含了静态资源如HTML页面或图片。
│   ├── index.html  # 页面模板.React 将目录 src 中的代码嵌入这个文件，从而浏览器才能运行此文件
├─ src   #TypeScript和CSS源码
│   ├─ index.tsx # 入口文件
│   ├─ App.tsx # 根组件
│   ├─ index.css # 全局样式
├─ package.json # 项目配置文件
├─ tsconfig.json # TypeScript配置文件
└─ README.md
```

### 前端项目架构概念
#### 路由（Route）
根据 URL来决定显示哪个组件或页面的机制.
让用户在应用程序中导航至不同的页面
#### 组件（Component）
将应用程序的不同部分划分为独立、可复用的模块。
组件可以包含 HTML、CSS 和 JavaScript，用于描述页面上的一部分或一个特定的功能
##### 组件库（Component Library）
包含多个可复用组件的集合。提供了常见的 UI 组件，如按钮、表单、模态框等，以及样式和交互行为
#### 状态（State）
应用程序的数据，例如用户信息、页面内容等。
##### 状态管理（State Management）
管理应用程序的状态，即数据，以便在应用程序的不同部分共享数据
常用的状态管理库包括 Redux、MobX 和 Vuex。
#### 样式预处理器（CSS Preprocessor）
样式预处理器是对原生 CSS 的扩展，提供更强大和灵活的样式编写能力。
常用的样式预处理器包括 Sass、Less 和 Stylus。
#### 打包工具（Bundler）
多个 JavaScript 文件、样式文件和其他资源文件。打包工具将这些文件打包成一个或多个最终的部署文件，以提高性能并简化部署过程。
常用的打包工具包括 webpack 和 Parcel。





### dev
```shell
npm run build
# 创建优化过的JS和CSS文件，./build/static/js和./build/static/css
```
