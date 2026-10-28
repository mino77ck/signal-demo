# SIGNAL — 灵感实验室

一个原生 HTML / CSS / JavaScript 构建的中文响应式示例网站。无构建工具、无第三方运行依赖。

## 功能

- 桌面与手机适配
- 深色 / 浅色主题，保存本地偏好
- 项目类型筛选与详情弹窗
- 可调频率的正弦波实验，支持播放 / 暂停
- 键盘导航与减少动态效果偏好支持

所有项目介绍均为概念演示，可替换为自己的真实项目。波形为数学可视化，不采集音频或个人数据。

## 本地查看

直接用浏览器打开 `index.html`，或在文件所在目录运行：

```sh
python3 -m http.server 8000
```

## GitHub Pages

在仓库 **Settings → Pages → Build and deployment** 中选择 **Deploy from a branch**，再选择 **main / (root)** 保存。后续修改 `index.html` 并提交到 `main` 后会自动重新发布。

## 自定义

页面样式、内容和交互全部位于 `index.html`。修改 `:root` 中的 CSS 变量可调整配色，修改 `details` 可调整项目详情。

## 许可

MIT License，详见 `LICENSE`。
