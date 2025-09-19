# 鲁虺抠图宝

一款基于AI技术的智能图片抠图工具，支持在浏览器本地完成图片背景去除及编辑操作，注重隐私保护且完全免费。

## 核心功能

- **AI一键抠图**：基于RMBG-1.4和MODNet模型实现高精度背景去除，无需手动操作
- **本地处理**：所有图片处理在浏览器中完成，无需上传至服务器，保护用户隐私
- **多场景编辑**：支持更换背景（纯色/图片/渐变）、调整亮度对比度、证件照尺寸设置等
- **批量处理**：支持同时上传多张图片进行批量抠图，提升效率
- **双模型支持**：
  - RMBG-1.4：轻量级通用模型，适配所有浏览器和设备
  - MODNet：WebGPU加速模型，在支持WebGPU的浏览器中处理速度提升一倍

## 技术栈

- **前端框架**：React
- **构建工具**：Vite
- **样式框架**：Tailwind CSS
- **AI推理**：Transformers.js
- **核心模型**：RMBG-1.4（Apache 2.0）、MODNet（MIT）
- **图标库**：Font Awesome（Font Awesome Free License）

## 部署指南

### Vercel 一键部署

1. 点击下方按钮跳转至Vercel部署页面
   [![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/kugeceo/cuttypic)
2. 登录Vercel账号（可使用GitHub账号授权）
3. 配置项目名称及环境变量（本项目无需特殊环境变量）
4. 点击"Deploy"按钮，等待部署完成
5. 部署成功后，Vercel会自动分配一个域名，可直接访问使用

### Netlify 一键部署

1. 点击下方按钮跳转至Netlify部署页面
   [![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/kugeceo/cuttypic)
2. 登录Netlify账号（可使用GitHub账号授权）
3. 确认仓库信息，点击"Deploy site"按钮
4. 等待构建部署完成（通常需要1-3分钟）
5. 部署成功后可在项目设置中自定义域名

## 本地开发

1. 克隆仓库
   ```bash
   git clone https://github.com/kugeceo/cuttypic.git
   cd cuttypic
   ```

2. 安装依赖
   ```bash
   npm install
   # 或使用yarn
   yarn install
   ```

3. 启动开发服务器
   ```bash
   npm run dev
   # 或使用yarn
   yarn dev
   ```

4. 打开浏览器访问 `http://localhost` 即可看到应用

## 使用技巧

- **提高处理速度**：
  - 浏览器支持WebGPU时，选择MODNet模型可获得更快速度
  - 处理前压缩大图片（建议不超过10MB）
  - 关闭其他占用资源的应用或标签页
  - 使用最新版本浏览器和高性能设备

- **优化抠图效果**：
  - 使用清晰、对比度高的图片
  - 确保主体与背景有明显区别
  - 复杂图片可尝试切换不同模型
  - 利用编辑工具（笔刷/橡皮擦）进行精细调整

- **场景化应用**：
  - 证件照：选择纯色背景+标准尺寸（一寸/二寸）
  - 电商图片：推荐白色背景提升专业感
  - 社交媒体：尝试渐变或图片背景增加吸引力

## 隐私说明

- 所有图片处理均在本地浏览器完成，不会上传至服务器
- 处理后的图片直接保存在用户设备中
- 不收集任何图片内容及个人信息
- 仅使用必要的Cookie存储用户偏好设置

## 开源许可证

本项目使用的开源组件及其许可证：
- React：MIT许可证
- Vite：MIT许可证
- Tailwind CSS：MIT许可证
- Transformers.js：Apache 2.0许可证
- RMBG-1.4：Apache 2.0许可证
- MODNet：MIT许可证
- Font Awesome：Font Awesome Free License

示例图片来自Unsplash，根据Unsplash许可证使用，允许免费使用、修改和分发，无需归属。

## 联系我们


- GitHub：https://github.com/kugeceo
- 微信：kugeceo
- 微博：http://weibo.com/kugeceo


## 捐助打赏作者

手机如何扫码：

[打赏作者](http://flash.luhui.net/images/zhifu.png)

① 保存上面二维码图片　② 打开微信、支付宝、手机qq、“扫一扫”　③ 点击右下脚图标　④ 选择刚才保存的图片

感谢每一位捐赠者，我一直在坚持不懈地努力和创新，不断精心打磨产品，并坚持完全免费，我走过的每一步、开发的每一个功能，离不开那些默默支持我的热心用户，
大家的每一份捐赠和建议，都是我做的更好、走的更远最大的支持和动力！感谢大家，感谢有你，与你相遇好幸运！

您的捐赠将会用于：

①  支付服务器、域名费用。
②  开发更丰富的功能，设计更友好的用户界面。
③  撰写发布更多文章，保证作者的官网一直免费为大家提供服务。


