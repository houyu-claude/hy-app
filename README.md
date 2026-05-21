# houyu-app

基于 **uni-app x** 框架的跨平台前端应用。

## 技术栈

- **框架**: uni-app x (Vue 3 + UTS)
- **语言**: UTS (TypeScript超集)
- **样式**: SCSS + rpx响应式单位
- **状态管理**: Vue 3 Composition API + reactive

## 项目结构

```
hy-app/
├── App.uvue                    # 应用入口组件
├── main.uts                    # 主入口文件
├── package.json                # 项目配置
├── manifest.json               # uni-app配置
├── pages.json                  # 页面路由配置
├── theme.json                  # 主题配置
├── uni.scss                    # SCSS样式变量
├── common/
│   └── uni.css                 # 公共样式
├── composables/
│   └── useDark.uts             # 暗黑模式组合式函数
├── components/
│   └── page-head/              # 页面头部组件
├── store/
│   └── index.uts               # 全局状态管理
├── pages/
│   ├── index/                  # 首页
│   └── mine/                   # 我的页面
└── static/
    └── tab/                    # TabBar图标
```

## 功能特性

- ✅ 跨平台支持（微信小程序、App、H5）
- ✅ 全局状态管理（系统信息、用户信息、生命周期计数）
- ✅ 暗黑模式检测
- ✅ 错误日志本地持久化
- ✅ TabBar导航
- ✅ 条件编译占位

## 开发

### 环境要求

- HBuilderX >= 3.99

### 运行方式

1. 使用 HBuilderX 打开项目
2. 选择运行目标：
   - 微信小程序
   - App（Android/iOS）
   - H5

## 构建

```bash
# 在HBuilderX中执行
# 微信小程序构建
# App构建
# H5构建
```

## 目录说明

| 目录 | 说明 |
|------|------|
| `common/` | 公共样式和工具函数 |
| `composables/` | Vue组合式函数 |
| `components/` | 可复用组件 |
| `store/` | 全局状态管理 |
| `pages/` | 页面文件 |
| `static/` | 静态资源 |

## 许可证

MIT License