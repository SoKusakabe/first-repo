# Git最小チートシート

## 日常フロー
```bash
# 1) ブランチ作成
git switch -c feature/xxx

# 2) 変更確認
git status
git diff

# 3) ステージ
git add <file>
git diff --staged

# 4) コミット
git commit -m "docs: update xxx"

# 5) push（初回は-u）
git push -u origin feature/xxx

# 6) PR作成（GitHub画面）
# 7) マージ後にmain同期
git switch main
git pull --rebase
```

## よく使う確認
```bash
git branch --show-current
git log --oneline --graph --decorate -n 10
git remote -v
```

## 取り消し系（安全側）
```bash
# 未ステージ変更を戻す
git restore <file>

# ステージだけ外す
git restore --staged <file>
```

## ページャー操作
- `(END)` が出たら `q` で終了
