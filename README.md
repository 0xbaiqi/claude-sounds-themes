# Claude Sounds Themes

[Claude Sounds Plugin](https://github.com/0xbaiqi/claude-sounds-plugin) 的主题仓库。

## 浏览主题

所有主题位于 [`themes/`](./themes/) 目录，每个主题有独立文件夹：

```
themes/
├── default/
│   ├── README.md          ← 创意说明 + 试听链接
│   └── default.cstheme    ← 主题包
├── cyberpunk/
│   ├── README.md
│   └── cyberpunk.cstheme
└── ...
```

点进每个主题的 `README.md` 可查看说明和试听链接。

## 安装主题

在 Claude Code 中：

```
/sounds:cs theme store list             查看所有可用主题
/sounds:cs theme store preview <name>   试听后决定是否安装
/sounds:cs theme store install <name>   直接安装
/sounds:cs theme <name>                 切换到该主题
```

## 提交主题

欢迎贡献你的主题！请阅读 [CONTRIBUTING.md](./CONTRIBUTING.md) 了解规范和流程。

简要步骤：

1. Fork 本仓库
2. 在 `themes/` 下新建文件夹，放入 `README.md` + `.cstheme` 文件
3. 更新 `index.json`
4. 提 PR

## 协议

MIT
