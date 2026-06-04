# 一些自的工具配置

## 安装字体

* Monaco Nerd Font

```shell
https://github.com/thep0y/monaco-nerd-font

# 下载字体
wget https://github.com/thep0y/monaco-nerd-font/releases/download/v0.2.1/MonacoNerdFont.zip 

# unzip 解压

# 全选安装字体
```

## Ghostty

* install ghostty

  - ubuntu

```shell
https://github.com/mkasberg/ghostty-ubuntu
```

  - macos

```shell
brew install --cask ghostty
```

* 热加载配置

```shell
Cmd+Shift+,
```

## 安装 starship

```shell
brew install starship
```

* 取消 .zshrc 配置文件中的 oh-my-zsh 的主题

```shell
# 禁用 oh-my-zsh 自带 theme
ZSH_THEME=""
```

* 添加 starship 加载

```shell
# Starship 作为最终 Prompt，放在 .zshrc 末尾
eval "$(starship init zsh)"
```

* 加载 zshrc

```shell
source ~/.zshrc
```

