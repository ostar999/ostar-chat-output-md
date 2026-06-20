# ostar-chat-output-md

导出 AI 助手（Claude Code、Cursor、Cline 等）当前会话聊天记录为 Markdown 格式。

支持多 Agent 平台，兼容 Claude Code、支持 Claude Code Skills 协议的其他 AI 编程助手。

## 触发词

- 导出聊天记录为markdown
- 导出聊天记录

## 功能说明

- **导出路径**：默认导出到本机 `~/Downloads/` 目录（非对话项目目录），用户可自定义路径
- **导出格式**：默认 Markdown 格式，用户可指定其他格式
- **导出内容**：默认导出会话完整聊天记录，不做总结，用户可另行指定

## 安装

### 方式一：通过 npx skills add（推荐）

```bash
npx skills add ostar999/ostar-chat-output-md
```

### 方式二：Git Clone

```bash
git clone https://github.com/ostar999/ostar-chat-output-md.git ~/.claude/skills/ostar-chat-output-md
```

克隆后在 Claude Code 中直接使用 `/ostar-chat-output-md` 触发，或配置到其他兼容 Agent 的 skills 目录中。
