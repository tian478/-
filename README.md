# 待办事项清单

一个基于 Vue.js 3 + Vite + Pinia + Vue Router 的工程化待办事项清单应用。

## 功能特性

- ✅ 添加待办事项
- ✅ 删除待办事项
- ✅ 清空所有待办事项
- ✅ 使用 Pinia 进行状态管理
- ✅ 使用 Vue Router 进行路由管理

## 技术栈

- Vue.js 3
- Vite
- Pinia (状态管理)
- Vue Router (路由管理)

## 项目结构

```
todo-list/
├── public/              # 静态资源
├── src/
│   ├── assets/         # 其他资源
│   ├── components/     # 组件
│   ├── router/         # Vue路由
│   ├── stores/         # 应用状态 (Pinia)
│   ├── views/          # 视图 (组件)
│   ├── App.vue         # 应用根组件
│   ├── main.js         # 整个项目入口文件
│   └── style.css       # 全局样式
├── index.html          # 主页面
├── package.json        # 应用包配置文件
├── vite.config.js      # Vite配置文件
└── README.md          # 应用说明文档
```

## 安装依赖

```bash
npm install
```

## 运行开发服务器

```bash
npm run dev
```

## 构建生产版本

```bash
npm run build
```

## 预览生产构建

```bash
npm run preview
```

