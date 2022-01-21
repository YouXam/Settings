# 配置

# 终端配置

使用 `oh-my-zsh`, 仅额外安装有 zsh-syntax-highlighting、zsh-autosuggestions, 主题使用 p10k。

## 未安装 `zsh`

```bash
sudo apt-get update && sudo apt-get install zsh -y && chsh -s /bin/zsh && wget -q -O /tmp/zsh.tar.gz https://cdn.jsdelivr.net/gh/youxam/settings@main/zsh.tar.gz && tar xzf /tmp/zsh.tar.gz -C ~
```

## 已安装 `zsh`

```bash
wget -q -O /tmp/zsh.tar.gz https://cdn.jsdelivr.net/gh/youxam/settings@main/zsh.tar.gz && tar xzf /tmp/zsh.tar.gz -C ~
```

然后重启终端。

若想对 p10k 配置， 只需要运行

```
p10k configure
```
