# -# 百应选品车一键抓取导出（独立版）

用于在巨量百应/罗盘选品车页面抓取商品数据，并支持导出或写入飞书。

## 安装方式

### 1. 安装 Tampermonkey
请先在浏览器安装 Tampermonkey 扩展。

### 2. 安装脚本
打开脚本发布页，点击“安装此脚本”。

### 3. 适用页面
- `https://buyin.jinritemai.com/*`
- `https://compass.jinritemai.com/*`

## 功能说明

1. 识别百应/罗盘选品车页面
2. 预加载滚动列表直到“没有更多”
3. 仅滚动列表区域，不滚整页
4. 抓取商品卡片数据
5. 支持飞书写入
6. 支持本地配置保存

## 文件说明

- `buyin_cart_export.user.js`：脚本主文件
- `LICENSE`：MIT 许可证
- `README.md`：项目说明

## 许可证

MIT
