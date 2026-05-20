# hy-app

基于 UniApp 的跨平台前端小程序

## 技术栈

- **框架**: UniApp 3.0
- **语言**: TypeScript 6.0
- **构建工具**: Vite 5.0
- **UI框架**: Vue 3.4

## 开发

```bash
# 安装依赖
npm install

# 开发模式 - H5
npm run dev:h5

# 开发模式 - 微信小程序
npm run dev:mp-weixin

# 构建 - H5
npm run build:h5

# 构建 - 微信小程序
npm run build:mp-weixin
```

## 支持平台

- H5
- 微信小程序 (mp-weixin)
- 支付宝小程序 (mp-alipay)
- 百度小程序 (mp-baidu)
- 字节跳动小程序 (mp-toutiao)
- QQ 小程序 (mp-qq)
- 京东小程序 (mp-jd)
- 快手小程序 (mp-kuaishou)
- 小红书小程序 (mp-xhs)
- 飞书小程序 (mp-lark)
- HarmonyOS (mp-harmony)
- 快应用 (quickapp-webview)

## 项目结构

```
hy-app/
├── src/
│   ├── pages/          # 页面目录
│   ├── static/         # 静态资源
│   ├── App.vue         # 应用根组件
│   ├── main.ts         # 入口文件
│   ├── manifest.json   # 应用配置
│   ├── pages.json      # 页面路由配置
│   ├── shims-uni.d.ts  # TypeScript 类型声明
│   └── uni.scss        # 全局样式变量
├── package.json
├── vite.config.ts
├── tsconfig.json
└── index.html
```
