# Contributing Themes

欢迎提交主题！请遵循以下规范。

## 文件结构

每个主题独立文件夹：

```
your-theme/
├── README.md           # 必须
└── your-theme.cstheme  # 必须
```

## README.md 必填内容

```markdown
# 主题名

> 一句话描述风格/创意

## 试听

| 事件 | 说明 | 试听 |
|------|------|------|
| Stop | 任务完成 | [链接]（可选） |
| Notification | 需要输入 | [链接]（可选） |
| Error | 出错 | [链接]（可选） |
| Permission | 工具调用前 | [链接]（可选） |

## 作者 / 协议

你的名字 · CC0 / MIT（必须是可自由使用的协议）
```

## 制作 .cstheme

1. 准备 4 个 MP3 文件和 manifest.json：

```
mytheme/
├── manifest.json
├── stop.mp3
├── notification.mp3
├── error.mp3
└── permission.mp3
```

`manifest.json` 格式：

```json
{
  "name": "mytheme",
  "display_name": "My Theme",
  "version": "1.0.0",
  "description": "简短描述",
  "author": "你的名字"
}
```

2. 打包（需已安装插件）：

```bash
bash ~/.claude/plugins/claude-sounds/scripts/manage.sh theme pack ./mytheme
```

或使用插件命令：

```
/sounds:cs theme pack ./mytheme
```

## 提交流程

1. Fork 本仓库
2. 新建文件夹，放入 `README.md` 和 `.cstheme` 文件
3. 更新根目录 `index.json`，加入你的主题条目
4. 提 PR，说明主题风格和音频来源

## 版权要求

- 音频必须是原创，或使用 CC0 / CC BY / MIT 等可自由使用的协议
- 禁止提交有版权争议的音频
