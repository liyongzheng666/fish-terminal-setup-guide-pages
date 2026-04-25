# Terminal Guide Pages

这个仓库用于发布轻量静态学习页，目前包含三条路线：

- [`index.html`](index.html)：基于 [`liyongzheng666/Terminal-setup`](https://github.com/liyongzheng666/Terminal-setup) 的 Fish 技术选型速查页。
- [`codex-terminal-skills/index.html`](codex-terminal-skills/index.html)：系统学习 Codex 终端常见命令、oh-my-codex 工作流与 Skill 调用技巧的路线图。
- [`claude-code-training/index.html`](claude-code-training/index.html)：系统学习 Claude Code CLI、斜杠命令、权限模式、MCP、Hooks、Subagents 与日常开发工作流的完整培训页。

Fish 页面重点覆盖：

- Fish 原生交互
- fzf 键盘集成
- zoxide / Fish `abbr` 命令捷径
- lazygit / btop / delta 基础键位

## 本地预览

直接打开对应 HTML 文件即可：

- `index.html`
- `codex-terminal-skills/index.html`
- `claude-code-training/index.html`

## 发布形态

这是纯静态站点，默认适合：

- GitHub Pages
- 任意静态文件托管

## 文件结构

- `index.html`: Fish Terminal Setup 快捷键图鉴
- `codex-terminal-skills/index.html`: Codex 终端与 Skill 系统学习路线
- `claude-code-training/index.html`: Claude Code 命令与操作完整培训
- `.nojekyll`: 禁用 Jekyll，按纯静态站点发布
