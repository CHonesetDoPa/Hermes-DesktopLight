
# Hermes Desktop Light

**轻量级 Windows 便携桌面客户端，连接部署在远程服务器上的 Hermes Agent。**

[![Build Light](https://github.com/CHonesetDoPa/Hermes-DesktopLight/actions/workflows/uild-desktop-light-windows.yml/badge.svg)](https://github.com/CHonesetDoPa/Hermes-DesktopLight/actions/workflows/uild-desktop-light-windows.yml)

Hermes Desktop Light 是基于官方 [NousResearch Hermes Agent](https://github.com/NousResearch/hermes-agent) 项目构建的非官方 Windows x64 社区版本。

本项目面向已经在 Ubuntu、Linux VPS 或其他远程服务器上部署 Hermes Agent 的用户。Windows 电脑只负责运行桌面 GUI 客户端，Hermes Agent 和 Gateway 则运行在远程服务器上。

> 本项目属于非官方社区构建版本，并非 NousResearch 官方发布。

[English](README.md)

## 项目特点

- 支持 Windows 10 / 11 x64。
- 基于官方 Hermes Desktop 源码。
- 使用官方 `light` 构建变体。
- 面向纯远程连接场景设计。
- 连接部署在远程服务器上的 Hermes Gateway。
- 使用 ZIP 便携压缩包分发。
- 不提供 MSIX 安装包。
- 通过 GitHub Actions 自动构建和发布。

## 下载

前往项目的 [Releases 发布页面](../../releases)，下载：

**Hermes-DesktopLight-Windows-x64.zip**

### 使用方法

1. 下载 Windows x64 ZIP 压缩包。
2. 将压缩包解压到任意目录。
3. 运行 `Hermes.exe`。
4. 配置远程 Hermes Gateway 连接。
5. 连接远程 Hermes Agent 并开始使用。

无需安装 MSIX。

## 运行要求

### Windows 客户端

- Windows 10 或 Windows 11，64 位。
- 可以访问远程 Hermes Gateway。
- 满足对应 Hermes Desktop 版本的运行要求。

### 远程服务器

- Ubuntu 或其他受支持的 Linux 发行版。
- 已安装并配置 Hermes Agent。
- Hermes Gateway 正在运行。
- 拥有可以从外部访问的 HTTPS 地址。
- 已正确配置 Gateway 身份验证。

## 重要说明

- 本项目是非官方社区维护的构建版本。
- 本项目与 NousResearch 没有隶属或官方背书关系。
- 软件基于 Hermes Agent 官方源码构建。
- `light` 变体的目标是纯远程连接模式。
- 设计上，Hermes Agent 和运行环境应保留在远程服务器。
- CI 构建成功并不代表已经证明应用首次启动时绝不会尝试安装本地运行环境。建议在一台干净的 Windows 电脑上进行首次启动测试。
- 实际兼容性取决于所选择的上游源码版本。

## 许可证与上游项目

Hermes Desktop Light 基于 Hermes Agent 官方项目构建。

- 上游项目：https://github.com/NousResearch/hermes-agent
- 上游许可证及版权声明：请参考上游仓库。
- 本仓库内容：社区构建工作流及 Release 打包配置。

重新分发或修改构建版本前，请仔细阅读上游项目的许可证及相关版权声明。
