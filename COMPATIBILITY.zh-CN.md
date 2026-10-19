# 应用兼容性

[English](COMPATIBILITY.md) · 简体中文 · [返回 README](README.zh-CN.md)

Here Button 依赖来源 App 通过 macOS 辅助功能提供的控件信息。以下仅记录具体测试版本和控件的限制，不代表应用的所有版本或功能均不支持；应用更新后，支持情况可能变化。

## 已知限制

### 微信

- **应用名称与版本：** 微信 macOS 4.1.15。
- **macOS 版本：** 此前测试记录未注明。
- **Here Button 版本：** 此前测试记录未注明。
- **受影响的页面或按钮：** 聊天界面和侧边栏中的按钮。
- **复现步骤：** 打开微信聊天界面，在 Here Button 中按 `Control + Option + P`，尝试选取聊天界面或侧边栏中的按钮。
- **预期结果 / 实际表现：** 预期可高亮并固定按钮；此前本机测试中未提供可用的辅助功能控件信息，实际无法选取或固定。
- **截图或录屏：** 未附。

## 补充不兼容应用

发现其他不兼容应用，或已有条目的支持情况发生变化，可[提交兼容性 Issue](https://github.com/locusable-studio/HereButton-Releases/issues/new?template=incompatible-app.yml)。提交前请先搜索[已有 Issues](https://github.com/locusable-studio/HereButton-Releases/issues)，相同应用和版本的情况可直接补充到原讨论中。

可使用以下简单模板，或填写链接中的 Issue 表单：

```text
应用名称与版本：
macOS 版本：
Here Button 版本：
受影响的页面或按钮：
复现步骤：
预期结果 / 实际表现：
截图或录屏（可选，请移除隐私信息）：
```
