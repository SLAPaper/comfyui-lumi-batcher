# ComfyUI Lumi Batcher

[English](./README.md) | 简体中文

## 概述

ComfyUI Lumi Batcher 是专为 ComfyUI 设计的批量处理扩展插件，旨在提升工作流调试效率。传统调试方式需要逐个参数调整，而本工具通过批量处理能力显著提升工作效率。

## 核心价值

### 传统调试痛点

- 手动逐个参数调整
- 难以管理参数组合（如图文对应关系）
- 耗时且容易出错

![传统方式](./static/old_way.png)

### 批量工具优势

- 一次性配置，自动执行多参数组合
- 可视化结果对比
- 支持多种输出类型（图片/文本/视频）

![批量工具](./static/new_way.png)

## 功能特性

### 核心功能

- 🚀 批量任务创建 ：智能参数叉乘生成
- 📊 任务管理 ：实时监控任务状态
- 🔍 结果对比 ：
  - 横向/纵向对比模式
  - 多模态支持（文本/图片/视频等）
- ⬇️ 结果导出 ：一键打包下载

## 安装指南

> 本地环境需要 Python3.10 以上版本

- 方式一：在 ComfyUI 的 CustomNode 目录，通过 git 命令拉取本项目，然后重启 ComfyUI 即可

```bash
git clone https://github.com/bytedance/comfyui-lumi-batcher.git
```

- 方式二：在 ComfyUI-Manager 中搜索`comfyui-lumi-batcher`，点击安装

安装完成后，在 ComfyUI 的 UI 面板中，默认在右上角位置，点击按钮，即可打开批量工具的界面。

## 新手帮助文档

[ComfyUI Lumi Batcher Using Tutorials](https://bytedance.larkoffice.com/docx/LGLWdPIj8ooQyxxMAOQcWmR8nCh)

## 工具架构图

![architecture](./static/architecture.png)
