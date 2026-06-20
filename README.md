# ostar-chat-output-md

导出 Claude Code 当前会话聊天记录为 Markdown 格式。

## 触发词

- 导出聊天记录为markdown
- 导出聊天记录

## 功能说明

- **导出路径**：默认导出到本机 `~/Downloads/` 目录（非对话项目目录），用户可自定义路径
- **导出格式**：默认 Markdown 格式，用户可指定其他格式
- **导出内容**：默认导出会话完整聊天记录，不做总结，用户可另行指定

## 安装

```bash
claude mcp add ostar-chat-output-md -- /Users/ouxingxing/.claude/skills/ostar-chat-output-md
```
