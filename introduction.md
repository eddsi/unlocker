# 在 Windows 虚拟机中安装 macOS 的详细指南

## 概述
购买一台苹果笔记本电脑可能代价昂贵，你可以通过在 Windows 虚拟机上安装 macOS 来体验苹果笔记本的功能。本教程将指导你如何使用 VMware 在 Windows 上虚拟安装 macOS。

## 准备工作
### 安装 VMware 虚拟机软件：
- 确保你的 Windows 电脑上已安装 VMware。
- 如果尚未安装，可以通过此链接下载并安装：[VMware 官方网站](https://www.vmware.com/products/workstation-pro.html)。
- 对于安装文件和更详细的安装指导，请参考 VMware 的官方文档。

### 下载 macOS 镜像和解锁工具：
- macOS Mojave 10.14 镜像文件（例如：Mojave 10.14 18A391 Lazy Installer.cdr）。
- unlocker（用于在 VMware 上解锁 macOS 安装选项）。
- 下载链接和提取码：[百度网盘](https://pan.baidu.com/s/1zL7-nB7ukif6nWBQ8KyOMA) 提取码: hrgr
- 下载链接中的unlocker不是最新的，直接拉取本仓库获取最新文件。

## 安装步骤
### 解锁 VMware 以安装 macOS：
1. 解压下载的 macOS Unlocker for VMware。
2. 右键 `win-install.cmd` 文件，并以管理员身份运行，以在 VMware 中解锁 macOS 安装选项。

### 创建新的 macOS 虚拟机：
1. 打开 VMware，选择“创建新的虚拟机”。
2. 使用下载的 `.cdr` 镜像文件作为启动光盘。
3. 如果系统提示无法识别操作系统，选择手动设置，并指定 macOS 版本。

### 配置和安装 macOS：
1. 继续按照 VMware 的指导进行虚拟机的配置，通常使用默认设置。
2. 启动虚拟机，开始 macOS 的安装过程。
3. 按照屏幕上的指示完成 macOS 的安装，包括磁盘格式化和操作系统安装。

### 首次启动和设置：
1. 安装完成后，启动 macOS 虚拟机。
2. 设置初始配置选项，如语言、账户信息等。

### 安装 VMware Tools（可选）：
- 在 macOS 虚拟机中安装 VMware Tools 以提高性能和用户体验。

## 使用建议
- 虚拟机可能会占用大量系统资源，确保你的物理机性能足够强大，以避免性能低下。
- 如果不使用虚拟机，确保及时关闭以释放资源。
- 虽然这种方式可以体验 macOS，但某些功能可能因虚拟化而受限。

## 总结
通过 VMware 在 Windows 虚拟机中安装 macOS 是一种成本效益高的方式，可以让用户在不购买昂贵硬件的情况下体验苹果的操作系统。跟随本指南，你将能够在你的 PC 上运行 macOS。
