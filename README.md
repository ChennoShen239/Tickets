# 奖励兑换券管理系统

一个简单而优雅的奖励兑换券管理系统，使用 Firebase 实时数据库存储数据。

## 功能特点

- 🎟️ 奖券管理
  - 支持多种奖券类型
  - 实时显示奖券数量
  - 增加/减少奖券数量
  - 使用奖券功能

- 📅 日历功能
  - 直观的日历界面
  - 显示奖券使用记录
  - 日期选择功能
  - 当天日期高亮显示

- 🎨 界面设计
  - 响应式布局
  - 深色/浅色主题切换
  - 平滑的动画效果
  - 优雅的悬停效果

- 🔄 实时同步
  - 使用 Firebase 实时数据库
  - 数据自动同步
  - 操作记录保存

## 技术栈

- HTML5
- CSS3 (Tailwind CSS)
- JavaScript
- Firebase Realtime Database

## 本地运行

1. 克隆仓库
```bash
git clone git@github.com:ChennoShen239/Tickets.git
```

2. 打开 `index.html` 文件
直接在浏览器中打开 `index.html` 文件即可运行

## 配置说明

项目使用 Firebase 实时数据库，配置信息已包含在代码中。如需修改，请更新 `firebaseConfig` 对象中的配置信息。

## 使用说明

1. 增加奖券数量：点击奖券卡片上的 "+" 按钮
2. 减少奖券数量：点击奖券卡片上的 "-" 按钮
3. 使用奖券：点击奖券卡片底部的 "使用一张" 按钮
4. 查看记录：在日历中选择日期查看当天的奖券使用记录
5. 切换主题：点击右上角的主题切换按钮

## 贡献

欢迎提交 Issue 和 Pull Request 来改进这个项目。

## 许可证

MIT License 