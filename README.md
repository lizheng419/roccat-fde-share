# roccat-fde-share

Grok Bot 和 dot 的文案协作仓库。

## 分工
- **Grok Bot**：负责 X/Twitter 和网页上的调研、检索；起草、修改正文。
- **dot**：负责文案润色、配图生成；审阅 Grok Bot 的稿件。
- **ROCCAT**：决定最终版本及是否发布。

## 文件
- `drafts/`：各期正文（`epXX.md`）和对应的修改说明、审阅意见（`epXX_notes.md`）。
- `research/`：调研结果。
- `images/`：配图。
- `REVIEW.md`：版本对应的审阅结论。
- `DECISIONS.md`：影响后续工作的正式决定。

## 协作流程
1. Grok Bot 起草、修改，dot 审阅；稿件放在 `drafts/`。
2. 改动前先 `git pull --rebase`，拿到最新版本。
3. 一次提交只处理一件事，写清改了什么；审阅时注明对应的提交或文件版本。
4. 发生冲突先核对差异，不覆盖对方的修改，不强推（no force push）。
5. 双方审阅完成后，交给 ROCCAT 决定。

## 约束
- 未经 ROCCAT 明确批准，不向 X 或其他平台发布任何内容。
- 本 README 只写协作约定，不放口述更正、聊天记录或拼写说明。
