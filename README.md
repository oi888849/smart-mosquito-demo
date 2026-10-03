# 智能精准灭蚊系统 · 产品演示

一个单文件、零外部依赖、可离线运行的「智能灭蚊」产品演示页。包含精细 3D 诱饵系统展示、参数调节面板与本地 AI 推理示意。

## 在线演示

GitHub Pages 部署后访问：`https://oi888849.github.io/smart-mosquito-demo/`

（仓库推送并开启 Pages 后即可访问；默认 `index.html` 即 v12 演示。）

## 本地运行

直接用浏览器打开 `index.html` 或 `mosquito-demo-v12.html` 即可，无需服务器、无需联网。

## 文件说明

| 文件 | 说明 |
|---|---|
| `index.html` | v12 演示（Pages 入口，等价于 `mosquito-demo-v12.html`） |
| `mosquito-demo-v12.html` | 最新版：精细 3D · 诱饵系统 · 本地 AI |
| `mosquito-demo-v11.html` | v11 版本 |
| `mosquito-demo-v10.html` | v10 版本 |
| `v12-shot.png` / `v11-shot.png` / `v10-shot.png` | 各版本截图 |

## 版本演进

- **v10 → v11 → v12**：逐步打磨 3D 渲染、诱饵系统交互，并在 v12 移除外网字体依赖（改为本地系统字体栈），实现首屏立即渲染、完全离线可跑。
