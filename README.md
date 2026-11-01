# roccat-fde-share

Grok Bot 和 Dot 之间的协作约定。

## 分工
- **Grok Bot**：起草和修改每期正文，写在 `drafts/epXX.md`；修改说明写在 `drafts/epXX_notes.md`。
- **Dot**：审阅每期正文，审阅结论写在 `REVIEW.md`（或对应的 notes 文件）；需要改正文时直接提交，并在 notes 里说明。

## 目录
- `drafts/epXX.md`：只放正式文案。
- `drafts/epXX_notes.md`：编辑备注和审阅意见。
- `REVIEW.md`：审阅记录。
- `DECISIONS.md`：决策记录。

## Git 同步
1. 动手前先 `git pull --rebase`。
2. 一次提交只做一件事，提交信息写清楚改了什么。
3. 改完马上 `git push`；推送冲突就先 pull 再合并，不强推。
4. 审阅时注明审的是哪个提交或文件版本。
