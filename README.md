# Claude Sounds Themes

Community theme store for the [Claude Sounds Plugin](https://github.com/0xbaiqi/claude-sounds-plugin).  
[Claude Sounds 插件](https://github.com/0xbaiqi/claude-sounds-plugin)的社区主题仓库。

## Available Themes / 可用主题

| Theme | Description | Author |
|-------|-------------|--------|
| [Default](./themes/default/) | Clean female voice prompts for daily use · 简洁干净的女声提示音 | 0xbaiqi |
| [Super Mario](./themes/mario/) | Mario coin pickup sound · 超级玛丽捡起金币音效 (CC0) | 0xbaiqi |
| [Chime](./themes/chime/) | Musical chime notification · 音乐铃声提示音 (CC0) | 0xbaiqi |

All themes are under [`themes/`](./themes/). Each folder contains a `README.md` with description and preview links.  
所有主题位于 [`themes/`](./themes/) 目录，每个主题的 `README.md` 包含说明和试听链接。

## Install a Theme / 安装主题

In Claude Code / 在 Claude Code 中：

```
/sounds:cs theme store list              List all available themes / 查看所有可用主题
/sounds:cs theme store preview <name>   Preview before installing / 试听后决定是否安装
/sounds:cs theme store install <name>   Install directly / 直接安装
/sounds:cs theme <name>                 Switch to theme / 切换到该主题
```

Or use the Web UI / 或使用图形界面：

```
/sounds:cs ui
```

Open the Store tab to browse, preview, and install themes with one click.  
打开 Store 标签页，一键浏览、试听、安装主题。

## Submit a Theme / 提交主题

Contributions are welcome! Read [CONTRIBUTING.md](./CONTRIBUTING.md) for guidelines.  
欢迎贡献你的主题！请阅读 [CONTRIBUTING.md](./CONTRIBUTING.md) 了解规范。

Quick steps / 简要步骤：

1. Fork this repo / Fork 本仓库
2. Create a folder under `themes/` with `README.md` + `.cstheme` / 在 `themes/` 下新建文件夹
3. Update `index.json`
4. Open a PR / 提 PR

## License / 协议

MIT — individual themes may have their own licenses, see each theme's README.  
MIT — 各主题音频可能有独立授权协议，详见各主题 README。
