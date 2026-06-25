# Dotfiles

我的个人 Linux 配置文件（使用 chezmoi 管理）。

## 在新电脑上初始化

1. 安装 `chezmoi` (如果是 Ubuntu/Debian):
   ```bash
   # 或者根据你的系统使用对应的安装方式
   sh -c "$(curl -fsLS chezmoi.io/get)"
   ```

2. 初始化并应用配置:
   ```bash
   chezmoi init --apply git@github.com:lubinglun/dotfile-Linux.git
   ```

3. 安装 Vim 插件 (打开 nvim 或 vim 后执行):
   ```vim
   :PlugInstall
   ```
