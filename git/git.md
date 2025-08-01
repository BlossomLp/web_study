# 合并提交
## 方法 1：使用 git commit --amend 修改最后一次提交
```bash
# 如果还没推送代码
git commit --amend

git commit --amend --date="2024-03-15T12:00:00" --no-edit
```
- `--date="YYYY-MM-DDTHH:MM:SS"` 设置新的 作者日期（Author Date）。

- `--no-edit 表示不修改提交信息。`

- 编辑框 `Esc` 输入 `:wq` 保存退出。
