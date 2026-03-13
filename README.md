# TuniaoUI Brand 2.0

一个基于 `uni-app + Vue2 + Tuniao UI` 的品牌商城模板项目，整体视觉偏简约、轻奢、时尚风，适合服饰、电商、品牌展示、小程序商城等场景快速改造。

项目采用首页沉浸式视频轮播、商品双列列表、购物车结算、订单流转、个人中心等完整商城页面结构，适合作为品牌商城前端模板或二次开发基础工程。

## 项目亮点

- 品牌感强：黑白灰为主的极简视觉，适合服饰、潮流、生活方式类商城
- 首页氛围足：支持全屏视频轮播与横向商品橱窗展示
- 商城链路完整：覆盖商品列表、商品详情、购物车、支付、订单、个人中心
- 组件化清晰：基于 `Tuniao UI` 组织页面，适合继续扩展业务模块
- 上手成本低：直接导入 `HBuilderX` 即可运行和预览

## 在线参考

- 官方模板页：[图鸟模板6-品牌商城](https://vue2.tuniaokj.com/theme/muse/tnmb6.html)

## 效果预览

以下展示图参考自官方模板页，用于帮助快速了解本项目整体风格与页面表现。

<p>
  <img src="https://cdn.nlark.com/yuque/0/2025/jpeg/280373/1737213305776-assets/web-upload/57b927e1-9a50-4248-8c86-db84e03d7620.jpeg" alt="官方预览图 1" height="220" />
  <img src="https://cdn.nlark.com/yuque/0/2025/jpeg/280373/1737213305280-assets/web-upload/0dae836b-54cd-455e-8067-b2b949de3873.jpeg" alt="官方预览图 2" height="220" />
  <img src="https://cdn.nlark.com/yuque/0/2025/jpeg/280373/1737213304935-assets/web-upload/d9689b15-fc2d-4299-8328-636839b97b55.jpeg" alt="官方预览图 4" height="220" />
  <img src="https://cdn.nlark.com/yuque/0/2025/jpeg/280373/1737213303368-assets/web-upload/95fea63d-e01b-47d0-9ac4-11dc88a54873.jpeg" alt="官方预览图 5" height="220" />
</p>

<p>
  <img src="https://cdn.nlark.com/yuque/0/2025/jpeg/280373/1737213303712-assets/web-upload/5d556d7b-85b8-4c12-9c0b-84ddb9db8788.jpeg" alt="官方预览图 7" height="220" />
  <img src="https://cdn.nlark.com/yuque/0/2025/jpeg/280373/1737213303760-assets/web-upload/4fdb3d57-d8d2-46b8-a2a6-b362c199947c.jpeg" alt="官方预览图 8" height="220" />
  <img src="https://cdn.nlark.com/yuque/0/2025/jpeg/280373/1737213303789-assets/web-upload/ffeb34d7-5d06-454f-b60e-4a8314d02336.jpeg" alt="官方预览图 9" height="220" />
</p>

<p>
  <img src="https://cdn.nlark.com/yuque/0/2025/jpeg/280373/1737213303684-assets/web-upload/d49964ca-1f06-483e-89f2-49183f4c8cbd.jpeg" alt="官方预览图 6" height="220" />
  <img src="https://cdn.nlark.com/yuque/0/2025/jpeg/280373/1737213306322-assets/web-upload/7e7076a0-5aa5-4a35-a83f-c9be1245699c.jpeg" alt="官方预览图 3" height="220" />
</p>

## 页面结构

### 主导航页面

- `pages/home/home.vue`：品牌首页，含视频轮播、品牌文案、橱窗展示
- `pages/product/product.vue`：商品列表，双列商品卡片 + 搜索区域
- `pages/cart/cart.vue`：购物车页面，支持商品数量调整与结算入口
- `pages/mine/mine.vue`：个人中心，包含订单、会员、个人信息、帮助中心等入口

### 子页面

- `productPages/details.vue`：商品详情页
- `cartPages/payment.vue`：订单支付页
- `minePages/order.vue`：订单列表页
- `minePages/order-details.vue`：订单详情页
- `minePages/set.vue`：个人信息设置
- `minePages/help.vue`：帮助中心
- `homePages/about.vue`：关于品牌页面

## 技术栈

- `uni-app`
- `Vue 2`
- `Tuniao UI`
- `SCSS`
- 微信小程序页面风格与交互写法

## 快速开始

### 1. 导入项目

使用 `HBuilderX` 打开项目根目录：

```bash
TuniaoUI_brand-2.0.0
```

### 2. 运行项目

在 `HBuilderX` 中选择：

- 运行到微信开发者工具
- 运行到浏览器
- 运行到手机或模拟器

### 3. 基础说明

- 项目首页入口为 `pages/index.vue`
- 页面配置位于 `pages.json`
- 全局样式位于 `uni.scss`
- UI 组件位于 `tuniao-ui/`
- 当前仓库内大部分商品、订单、个人信息均为演示数据

## 适用场景

- 品牌商城小程序
- 服饰鞋包类商城
- 轻奢生活方式电商
- 企业品牌展示与商品陈列
- 需要快速搭建高颜值商城前端的 uni-app 项目

## 开发建议

- 若用于正式项目，建议先替换商品图片、品牌文案、价格与个人中心示例数据
- `homePages/about.vue` 当前仍为占位内容，建议按业务补充品牌介绍
- 远程图片资源较多，如需离线部署，建议迁移为自有静态资源

## 致谢

本项目基于 `Tuniao UI` 生态模板整理，页面风格与展示图参考图鸟官方模板页。
