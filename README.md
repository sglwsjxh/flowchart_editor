# 🎨 Workflow Canvas – 轻量级工作流绘制工具

> 一个基于原生 JavaScript 和 Canvas 的**零依赖**工作流编辑器。  
> 拖拽节点、连接端口、编辑属性、保存/打开文件……所有操作都在浏览器中完成，即开即用。

<p align="center">
  <img src="https://img.shields.io/badge/license-MIT-green" alt="MIT License">
  <img src="https://img.shields.io/badge/平台-Web-blue" alt="Platform">
  <img src="https://img.shields.io/badge/依赖-无-orange" alt="Dependencies">
</p>

---

## ✨ 功能特性

- **节点拖拽创建** – 从左侧节点库直接拖放到画布
- **节点自由拖拽** – 任意移动节点位置
- **可调整大小** – 每个节点右下角均有调整手柄，自由缩放
- **智能连线** – 从输出端口（橙色）拖动到输入端口（青色）自动创建连线；同一输入端口只允许一条连线
- **多种节点类型** – 开始、处理、结束、条件分支、合并节点，不同颜色区分，端口数量符合逻辑
- **属性编辑** – 选中节点后右侧面板出现，实时修改节点标题
- **撤销 / 重做** – 支持多步历史记录，放心编辑
- **保存 / 打开** – 将工作流保存为 JSON 文件，也可加载本地文件继续编辑
- **视图操作** – 滚轮缩放、空白区域拖拽平移、一键适应视图
- **删除与复制** – 选中节点或连线后按 `Delete` 删除；选中节点按 `Ctrl+C` 快速复制（带偏移）

---

## 🚀 快速开始

### 方式一：直接使用HTML版本
1. 下载 [`index.html`](./index.html) 文件到本地
2. 直接使用现代浏览器打开该文件
3. 开始绘制你的第一个工作流！

### 方式二：下载Windows便携版exe（推荐Windows用户）
前往 [Releases页面](https://github.com/sglwsjxh/flowchart_editor/releases) 下载最新版本的 `流程图编辑器.exe` 文件，双击即可运行。

### 方式三：从源码构建
```bash
# 克隆项目
git clone https://github.com/sglwsjxh/flowchart_editor.git
cd flowchart_editor

# 安装依赖
npm install

# 启动项目
npm start

# 生成便携式exe
npm run build-portable
```

## 📄 许可证

本项目基于 MIT 许可证开源

详细条款请参见 [LICENSE](LICENSE) 文件

---

**Happy Workflow Building!** 🚀