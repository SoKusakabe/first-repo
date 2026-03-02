# GitHub学習計画

最終更新日: 2026-03-02

## 目標
- Git/GitHubの基本操作を自力で回せるようにする
- `main` へ直接作業せず、`feature/*` ブランチ運用を習慣化する
- PR作成からマージ、同期、ブランチ削除までを一連で行えるようにする

## 現在地（完了済み）
- [x] リポジトリのクローン
- [x] `add -> commit -> push` の実行
- [x] `feature/readme-update` ブランチでの作業
- [x] PR作成
- [x] PRマージ
- [x] `main` の同期（`git pull --rebase`）
- [x] ローカル/リモートのfeatureブランチ削除
- [x] Git基本設定（`user.name`, `user.email`, `pull.rebase`）

## 学習ロードマップ
### Phase 1: 基本反復（2-3回）
- 同じ流れを別ファイルで繰り返す
- コマンドを見ずに実行できることを目標にする

### Phase 2: 実務の基本
- `.gitignore` を理解して設定する
- コミットメッセージ規約（例: `feat:`, `fix:`, `docs:`）を使う
- `git log --oneline --graph --decorate` を読めるようにする

### Phase 3: トラブル対応
- コンフリクト解消
- 誤って `add` した変更の取り消し
- 誤ったコミットメッセージの修正（`--amend`）

## 次にやること（次回）
1. `feature/practice-2` ブランチを作る
2. `README.md` または新規ファイルを1つ更新
3. PR作成〜マージ〜同期までを再実施
4. `session-log.md` に結果を追記
