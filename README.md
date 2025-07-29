# zshrc_custom

你可以使用以下命令从 GitHub 上下载 `.zshrc_custom` 文件并复制到用户的主目录 (`~`)：

```bash
curl -o ~/.zshrc_custom https://raw.githubusercontent.com/cloudsmithy/zshrc_custom/master/.zshrc_custom
```

解释：

1. `curl -o ~/.zshrc_custom`：使用 `curl` 命令将文件下载并保存为 `~/.zshrc_custom`。
2. `https://raw.githubusercontent.com/cloudsmithy/zshrc_custom/master/.zshrc_custom`：这是 `.zshrc_custom` 文件的原始下载链接。

这样，你就能直接将 `.zshrc_custom` 文件下载并放到主目录下。



你可以直接执行 `install.sh` 脚本来安装依赖，使用以下命令：

```bash
curl -sSL https://raw.githubusercontent.com/cloudsmithy/zshrc_custom/master/install.sh | zsh
```

解释：

1. `curl -sSL`：下载脚本并且确保 HTTPS 链接的重定向可以正确处理。
2. `https://raw.githubusercontent.com/cloudsmithy/zshrc_custom/master/install.sh`：这是 `install.sh` 文件的原始链接。
3. `| zsh`：将下载的脚本通过管道传输到 `bash`，直接执行。

这样，脚本会自动执行安装步骤并将 `.zshrc_custom` 设置应用到你的系统中。
