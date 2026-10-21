# ☁️ Cloud Linux Dev Environment (GitHub Codespaces)

这是一个基于 **GitHub Codespaces** 和 **Dev Containers** 构建的全功能云端 Linux 开发环境。

## 📦 环境内置配置

- **操作系统**: Ubuntu 22.04 LTS (Linux)
- **Shell**: Zsh (开箱即用高颜值终端环境)
- **编程语言与工具栈**:
  - **Python**: Python 3.x、`pip`、`virtualenv`
  - **Node.js**: Node.js LTS、`npm`、`pnpm`、`yarn`
  - **C / C++**: `gcc`、`g++`、`clang`、`cmake`、`gdb`、`make`
  - **Docker**: Docker-in-Docker（支持在云主机中构建和运行容器）
  - **基础工具**: `git`、`curl`、`wget`、`build-essential`、`htop`、`jq` 等

---

## 🚀 如何使用该云端环境

### 方式 1：直接在浏览器中使用（最简单）
1. 在本仓库主页，点击绿色的 **Code** 按钮。
2. 切换到 **Codespaces** 选项卡。
3. 点击 **Create codespace on main**。
4. 等待 1~2 分钟初始化完成，即可在浏览器中获得一个包含完整终端、代码编辑器与扩展的 Linux VS Code 界面！

### 方式 2：使用本地 VS Code 连接
1. 在本地 VS Code 中安装插件 **GitHub Codespaces**。
2. 按 `Ctrl+Shift+P`（macOS 为 `Cmd+Shift+P`），输入 `Codespaces: Connect to Codespace...`。
3. 选择你的云端环境即可在本地窗口流畅操作云端文件和终端。

### 方式 3：使用 SSH / 终端直连
使用本机终端运行：
```bash
gh codespace ssh
```
即可直接登录云端 Linux bash/zsh 命令行。
