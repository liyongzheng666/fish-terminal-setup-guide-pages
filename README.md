# Ally Guide Pages

这个仓库用于统一发布轻量静态学习网页。后续 Fish、tmux、Codex、Claude Code 这类网页都在本地和远端同一个仓库维护。

- [`index.html`](index.html)：所有指南页的总入口。
- [`fish-terminal-setup/index.html`](fish-terminal-setup/index.html)：基于 [`liyongzheng666/Terminal-setup`](https://github.com/liyongzheng666/Terminal-setup) 的 Fish 技术选型速查页。
- [`tmux-ghostty-guide/index.html`](tmux-ghostty-guide/index.html)：面向 Mac + Ghostty 用户的 tmux 新手分享页。
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
- `fish-terminal-setup/index.html`
- `tmux-ghostty-guide/index.html`
- `codex-terminal-skills/index.html`
- `claude-code-training/index.html`

## 发布形态

这是纯静态站点，默认适合：

- GitHub Pages
- 任意静态文件托管

## 文件结构

- `index.html`: 指南书架总入口
- `fish-terminal-setup/index.html`: Fish Terminal Setup 快捷键图鉴
- `tmux-ghostty-guide/index.html`: tmux × Ghostty 新手指南
- `codex-terminal-skills/index.html`: Codex 终端与 Skill 系统学习路线
- `claude-code-training/index.html`: Claude Code 命令与操作完整培训
- `tmux-ghostty-guide/assets/`: tmux 指南社交分享图
- `.nojekyll`: 禁用 Jekyll，按纯静态站点发布
