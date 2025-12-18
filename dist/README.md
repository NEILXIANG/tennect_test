# Hello World 可执行文件

## 文件说明

- `main` - macOS 命令行可执行文件（推荐使用）
- `main.app` - macOS 应用程序包

## 使用方法

### 命令行版本（推荐）
```bash
./main
```

### 应用程序版本
```bash
open main.app
```

## 特性

- 无需安装 Python 环境
- 可直接复制到其他 macOS 机器运行
- 单文件分发，方便部署
- 支持 Intel 和 Apple Silicon Mac

## 系统要求

- macOS 10.13 或更高版本
- Intel 或 Apple Silicon Mac

## 分发

将 `main` 文件复制到目标机器，赋予执行权限后即可运行：

```bash
chmod +x main
./main
```