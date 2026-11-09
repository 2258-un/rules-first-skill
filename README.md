# 先定规则，再动手

这是一个 Codex Skill，适用于数据分析工具、自动化脚本和已有工具的修改。它按 Specify → Plan 评审 → Implement → Validate 推进，每次按用户指定的任务执行，并把验收证据写入项目文档。

## 在另一台电脑安装

用有权访问此仓库的 GitHub 账号登录。私有仓库需要让 Git 在该电脑上具备读取权限。复制此仓库的链接，在目标电脑的 Codex 聊天中发送下面这条消息，把「仓库链接」替换成实际链接。

> 请使用 $skill-installer，从「仓库链接」安装 `skills/rules-first`。

安装后，在 Codex 聊天中发送：

> 请使用 $rules-first 开发这个工具，先完成 Specify。

接续项目时发送「请使用 $rules-first，执行 topic-open」。完成任务后用「请使用 $rules-first，执行 topic-save」保存进度。

仓库保存 Skill、模板和小麦施肥示例。实际项目规则和进度留在各自的项目目录中。
